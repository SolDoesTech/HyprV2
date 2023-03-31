# HyprV2
An improved Hyprland deployment

collection of dot config files for hyprland with a simple install script for a fresh Arch linux with yay

You can grab the config files and install packages by hand with this commnad
```
yay -S hyprland-bin kitty waybar-hyprland \
    swww swaylock-effects wofi wlogout mako \
    ttf-jetbrains-mono-nerd noto-fonts-emoji \
    polkit-gnome python-requests starship \
    swappy grim slurp pamixer pavucontrol brightnessctl \
    bluez bluez-utils blueman network-manager-applet \
    lxappearance xfce4-settings xdg-desktop-portal-hyprland-git \
    thunar gvfs thunar-archive-plugin file-roller \
    sddm-git sddm-sugar-candy-git
```

Or you can use the attached script "set-hypr" to install everything for you.
