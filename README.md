# **`azeem30's` Hyprland Dotfiles**

> ![](https://ziadoua.github.io/m3-Markdown-Badges/badges/Arch/arch1.svg)
> ![](https://ziadoua.github.io/m3-Markdown-Badges/badges/CSS/css1.svg)
> ![](https://ziadoua.github.io/m3-Markdown-Badges/badges/Linux/linux2.svg)
> ![](https://ziadoua.github.io/m3-Markdown-Badges/badges/Shell/shell3.svg)
> ![](https://ziadoua.github.io/m3-Markdown-Badges/badges/Neovim/neovim1.svg)
> [<img src="https://m3-markdown-badges.vercel.app/stars/1/1/shub39/dotfiles">]()

## Screenshots
![1](screenshots/1.png)
![2](screenshots/2.png)
![3](screenshots/3.png)
![4](screenshots/4.png)

## Packages

### Official Repo
Needed
```
ttf-jetbrains-mono ttf-jetbrains-mono-nerd hyprpicker hyprpaper neovim hyprpolkitagent nwg-look noto-fonts noto-fonts-emoji noto-fonts-extra swaync waybar hyprlock gnome-terminal chromium cava scrcpy nemo rofi-wayland cmus copyq flatpak fastfetch imagemagick
```

My preferred extras
```
vlc loupe gnome-boxes gnome-disk-utility gnome-system-monitor nemo-fileroller
```

### AUR
```
gruvbox-dark-icons-gtk gruvbox-material-gtk-theme-git hyprshot wlogout zen-browser-bin
```

### Flatpak
```
it.mijorus.smile
```

## Installation

- Clone this repo at `.config/` in your home directory

```bash
git clone https://github.com/azeem30/dotfiles
```

- Edit `~/.config/hypr/hyprland.conf` to only include `source = ~/.config/dotfiles/hyprland/hyprland.conf`
```bash
echo 'source = ~/.config/dotfiles/hyprland/hyprland.conf' > ~/.config/hypr/hyprland.conf
```

- Reboot
