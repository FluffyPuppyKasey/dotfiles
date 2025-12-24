# Quickstart
Fedora:
```bash
sudo dnf update
sudo dnf install --nogpgcheck --repofrompath 'terra,https://repos.fyralabs.com/terra$releasever' terra-release
sudo dnf copr enable erikreider/swayosd
sudo dnf install rofi alacritty swww swaybg waybar mako grim wl-clipboard cava wlogout fontawesome-fonts-all mangowc swayosd nmtui
chezmoi init https://github.com/FluffyPuppyKasey/dotfiles.git
```
