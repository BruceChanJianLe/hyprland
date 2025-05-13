# Hyprland

This is really not beginner friendly...Oh well, let's go!

## Prerequisite (Basics)

```bash
sudo pacman -S dolphin dunst grim hyprland kitty polkit-kde-agent qt5-wayland qt6-wayland wofi slurp xdg-desktop-portal-hyprland
sudo pacman -S iwd openssh smartmontools wpa_supplicant xdg-utils wireless_tools
```

Software | Description
---|---
dolphin                       | KDE File Manager
dunst                         | Customizable and lightweight notification-daemon
grim                          | Screenshot utility for Wayland
hyprland                      | a highly customizable dynamic tiling Wayland compositor
kitty                         | A modern, hackable, featureful, OpenGL-based terminal emulator
polkit-kde-agent              | Daemon providing a polkit authentication UI for KDE
qt5-wayland                   | Provides APIs for Wayland
qt6-wayland                   | Provides APIs for Wayland
slurp                         | Select a region in a Wayland compositor
wofi                          | launcher for wlroots-based wayland compositors
xdg-desktop-portal-hyprland   | xdg-desktop-portal backend for hyprland

Software | Description
---|---
iwd              | Internet Wireless Daemon
openssh          | SSH protocol implementation for remote login, command execution and file transfer
smartmontools    | Control and monitor S.M.A.R.T. enabled ATA and SCSI Hard Drives
wpa_supplicant   | A utility providing key negotiation for WPA wireless networks
xdg-utils        | Command line tools that assist applications with a variety of desktop integration tasks
wireless_tools   | Tools allowing to manipulate the Wireless Extensions

## Ricing Options

- Status Bar: waybar (requires font-awesome)
- File Manager: nautilus
- Terminal: Ghostty
- ScreenShot: hyprshot ❌
- Notification Center: swaync ❌
- Lock Screen: hyprlock ❌
- Screen Saver: hypridle ❌
- Wall Paper: hyprpaper ❌

Preferred hyprland ecosystem list (https://wiki.hyprland.org/Hypr-Ecosystem/).

## Reference

- https://wiki.hyprland.org/Nix/Hyprland-on-Home-Manager/
- https://pq.hosting/en/help/kak-ustanovit-hyprland-na-ubuntu-2404#:~:text=Note%20that%20only%20the%20version,that%20changes%20dependency%20requirements%20frequently.
- GNOME with Hyprland: https://dev.to/renhiyama/how-to-dualboot-hyprland-with-gnome-desktops-on-linux-1pa4
