<div align="center">
  <h1>Arch with Hyprland Dots</h1>
  <img width="200" src="https://raw.githubusercontent.com/maaaz15/dots/main/source/assets/ArchLinux.svg">
  <br>
  <br>
  <img src="https://img.shields.io/github/last-commit/maaaz15/dots?style=for-the-badge&color=ffb4a2&labelColor=201a19">
  <img src="https://img.shields.io/github/stars/maaaz15/dots?style=for-the-badge&color=e6c419&labelColor=1d1b16">
  <img src="https://img.shields.io/github/repo-size/maaaz15/dots?style=for-the-badge&color=a8c7ff&labelColor=1a1b1f">
</div>

## About

This is a fork of [hyprdots](https://github.com/klpod221/klpod0s) with heavy changes to make it work on my system and to my liking. I have also added some of my own scripts and configs to make it work better for me and maybe for you too.

### Installation

The installation script is made for Arch, but **may** work on some Arch based distros.

After minimal Arch install (with grub), clone and execute -

```shell
pacman -Sy git
git clone https://github.com/maaaz15/dots.git ~/dots
cd ~/dots
./install.sh
```

Please reboot after the install script completes and takes you to sddm login screen (or black screen) for the first time.

### Theming

The theme used throughout is Catppuccin with Mocha variant.

## Packages

<table><tr><td>
<code>u</code><br><code>t</code><br><code>i</code><br><code>l</code><br><code>s</code></td><td><table>
    <tr><td>pipewire</td><td>audio and video server</td></tr>
    <tr><td>pipewire-alsa</td><td>for audio</td></tr>
    <tr><td>pipewire-audio</td><td>for audio</td></tr>
    <tr><td>pipewire-jack</td><td>for audio</td></tr>
    <tr><td>pipewire-pulse</td><td>for audio</td></tr>
    <tr><td>gst-plugin-pipewire</td><td>for audio</td></tr>
    <tr><td>wireplumber</td><td>audio and video server</td></tr>
    <tr><td>networkmanager</td><td>network manager</td></tr>
    <tr><td>network-manager-applet</td><td>nm tray</td></tr>
    <tr><td>bluez</td><td>for bluetooth</td></tr>
    <tr><td>bluez-utils</td><td>for bluetooth</td></tr>
    <tr><td>blueman</td><td>bt tray</td></tr></table>
</td></tr></table>

<table><tr><td>
<code>l</code><br><code>o</code><br><code>g</code><br><code>i</code><br><code>n</code></td><td><table>
    <tr><td>sddm-git</td><td>display manager for login</td></tr>
    <tr><td>qt5-wayland</td><td>for QT wayland XDP</td></tr>
    <tr><td>qt6-wayland</td><td>for QT wayland XDP</td></tr>
    <tr><td>qt5-quickcontrols</td><td>for sddm theme</td></tr>
    <tr><td>qt5-quickcontrols2</td><td>for sddm theme</td></tr>
    <tr><td>qt5-graphicaleffects</td><td>for sddm theme</td></tr></table>
</td></tr></table>

<table><tr><td>
<code>h</code><br><code>y</code><br><code>p</code><br><code>r</code></td><td><table>
    <tr><td>hyprland-git</td><td>main window manager (hyprland-nvidia-git if nvidia card is detected)</td></tr>
    <tr><td>dunst</td><td>graphical notification daemon</td></tr>
    <tr><td>rofi-lbonn-wayland-git</td><td>app launcher</td></tr>
    <tr><td>waybar-hyprland-git</td><td>status bar</td></tr>
    <tr><td>swww</td><td>wallpaper app</td></tr>
    <tr><td>swaylock-effects-git</td><td>lockscreen</td></tr>
    <tr><td>wlogout</td><td>logout screen</td></tr>
    <tr><td>grimblast-git</td><td>screenshot tool</td></tr>
    <tr><td>slurp</td><td>selects region for screenshot/screenshare</td></tr>
    <tr><td>swappy</td><td>screenshot editor</td></tr>
    <tr><td>cliphist</td><td>clipboard manager</td></tr></table>
</td></tr></table>

<table><tr><td>
<code>d</code><br><code>e</code><br><code>p</code><br><code>e</code><br><code>n</code><br><code>d</code><br><code>e</code><br><code>n</code><br><code>c</code><br><code>y</code></td><td><table>
    <tr><td>polkit-kde-agent</td><td>authentication agent</td></tr>
    <tr><td>xdg-desktop-portal-hyprland</td><td>XDG Desktop Portal</td></tr>
    <tr><td>pacman-contrib</td><td>for system update check</td></tr>
    <tr><td>python-pyamdgpuinfo</td><td>for amd gpu info</td></tr>
    <tr><td>parallel</td><td>for parallel processing</td></tr>
    <tr><td>jq</td><td>to read json</td></tr>
    <tr><td>imagemagick</td><td>for image processing</td></tr>
    <tr><td>qt5-imageformats</td><td>for dolphin image thumbnails</td></tr>
    <tr><td>ffmpegthumbs</td><td>for dolphin video thumbnails</td></tr>
    <tr><td>brightnessctl</td><td>brightness control for laptop</td></tr>
    <tr><td>pavucontrol</td><td>audio settings gui</td></tr>
    <tr><td>pamixer</td><td>for waybar audio</td></tr>
    <tr><td>fcitx5</td><td>for input method</td></tr>
    <tr><td>fcitx5-qt</td><td>for input method</td></tr>
    <tr><td>fcitx5-gtk</td><td>for input method</td></tr>
    <tr><td>fcitx5-configtool</td><td>for input method</td></tr></table>
</td></tr></table>

<table><tr><td>
<code>t</code><br><code>h</code><br><code>e</code><br><code>m</code><br><code>e</code></td><td><table>
    <tr><td>nwg-look</td><td>theming GTK apps</td></tr>
    <tr><td>kvantum</td><td>theming QT apps</td></tr>
    <tr><td>qt5ct</td><td>theming QT5 apps</td></tr></table>
</td></tr></table>

<table><tr><td>
<code>a</code><br><code>p</code><br><code>p</code><br><code>s</code></td><td><table>
    <tr><td>firefox</td><td>browser</td></tr>
    <tr><td>brave-bin</td><td>browser</td></tr>
    <tr><td>kitty</td><td>terminal</td></tr>
    <tr><td>neofetch</td><td>fetch tool</td></tr>
    <tr><td>btop</td><td>system monitor</td></tr>
    <tr><td>thunar</td><td>xfce file manager</td></tr>
    <tr><td>visual-studio-code-bin</td><td>gui code editor</td></tr>
    <tr><td>neovim</td><td>text editor</td></tr>
    <tr><td>ark</td><td>kde file archiver</td></tr></table>
</td></tr></table>

<table><tr><td>
    <code>s</code><br><code>h</code><br><code>e</code><br><code>l</code><br><code>l</code></td><td><table>
    <tr><td>zsh</td><td>main shell</td></tr>
    <tr><td>lsd</td><td>colorful file lister</td></tr>
    <tr><td>fzf</td><td>command line fuzzy finder</td></tr>
    <tr><td>cava</td><td>audio visualizer</td></tr></table>
</td></tr></table>
