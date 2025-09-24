---
title: Dotfiles
published: 2024-07-16
description: 🤖 My hyprland configuration (I use Arch btw)
tags: [Linux, Shell, Configs]
category: Linux
image: https://raw.githubusercontent.com/shub39/dotfiles/main/screenshots/1.png
draft: false
---

![2](https://raw.githubusercontent.com/shub39/dotfiles/main/screenshots/2.png)
![3](https://raw.githubusercontent.com/shub39/dotfiles/main/screenshots/3.png)
![4](https://raw.githubusercontent.com/shub39/dotfiles/main/screenshots/4.png)

::github{repo="shub39/dotfiles"}

:::warning
You should be familiar with Linux first before using any Tiling window manager, I recommend spending a few months with Linux Mint and getting familiar with  
the terminal. 

The beauty of Linux is that it's highly customizable and allows you to create your own workflow. With a little bit of effort, you can make your desktop environment feel like your own personal space. You *will* face issues in that case you can reach out to me on discord `@shub39` and I'll try to help you if possible. 
:::

## Packages

### Official Repo
Needed
```
ttf-jetbrains-mono ttf-jetbrains-mono-nerd hyprpicker hyprpaper neovim hyprpolkitagent nwg-look noto-fonts noto-fonts-emoji noto-fonts-extra swaync waybar hyprlock gnome-terminal chromium cava scrcpy nemo rofi-wayland cmus copyq flatpak fastfetch imagemagick
```

My preferred extras
```
mpv loupe gnome-boxes gnome-disk-utility gnome-system-monitor nemo-fileroller
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
git clone https://github.com/shub39/dotfiles
```

- Edit `~/.config/hypr/hyprland.conf` to only include `source = ~/.config/dotfiles/hyprland/hyprland.conf`
```bash
echo 'source = ~/.config/dotfiles/hyprland/hyprland.conf' > ~/.config/hypr/hyprland.conf
```

- Reboot

## Extras

- [NvChad](https://nvchad.com/) a preconfigured neovim setup
- [Zsh config](https://github.com/pixegami/terminal-profile) for this setup, **edit the scripts according to your package manager first**