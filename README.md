# Quickstart
Fedora:
```bash
sudo dnf update
sudo dnf install --nogpgcheck --repofrompath 'terra,https://repos.fyralabs.com/terra$releasever' terra-release
sudo dnf copr enable erikreider/swayosd
sudo dnf install rofi alacritty swww swaybg waybar mako grim wl-clipboard cava wlogout fontawesome-fonts-all mangowc swayosd nmtui oxygen-fonts oxygen-icon-theme oxygen-sounds plasma-oxygen chezmoi
chezmoi init https://github.com/FluffyPuppyKasey/dotfiles.git
```
Oneliner: `sudo dnf update && sudo dnf install --nogpgcheck --repofrompath 'terra,https://repos.fyralabs.com/terra$releasever' terra-release && sudo dnf copr enable erikreider/swayosd && sudo dnf install rofi alacritty swww swaybg waybar mako grim wl-clipboard cava wlogout fontawesome-fonts-all mangowc swayosd nmtui oxygen-fonts oxygen-icon-theme oxygen-sounds plasma-oxygen chezmoi && chezmoi init https://github.com/FluffyPuppyKasey/dotfiles.git`
