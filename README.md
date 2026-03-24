# Hyprland Dots

Minimal [Hyprland](https://hyprland.org/) configuration for Arch-based systems, built around productivity, speed, and efficiency.

## System

| Component | Choice |
|-----------|--------|
| WM | Hyprland (Wayland) |
| Terminal | foot |
| Bar | Waybar |
| Launcher | Fuzzel |
| File manager | Yazi |
| Notifications | Mako |
| Lock screen | Hyprlock |
| Idle daemon | Hypridle |
| Wallpaper | Hyprpaper |
| Theme | Tokyo Night |
| Font | JetBrains Mono |

## Structure

```
~/.config/hypr/
├── hyprland.conf      # core settings, monitors, env vars, includes
├── hypridle.conf      # idle timeout and DPMS
├── hyprlock.conf      # lock screen appearance
├── hyprpaper.conf     # wallpaper config
└── hyprsunset.conf    # blue light filter
```

## Philosophy

- Both keybind & mouse focused workflow is supported
- Gamemode script available for better performance on lower end hardware
- All in one fuzzel configuration (application launcher, network menu, clipboard menu & power options menu)
- Customized window layouts for each workspace

## Usage

Clone and symlink or copy to `~/.config/hypr/`:

```bash
git clone https://github.com/Hexanchus29/dotfiles.git
cp -r dotfiles/* ~/.config/hypr/
```

Review `hyprland.conf` before applying, you will need to change paths and you will be able to change keybinds to your liking.
