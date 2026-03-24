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

- Keybinds are muscle-memory first — consistent modifiers, no conflicts
- Window rules are explicit, not assumed
- Animations are present but fast — feedback without friction
- Dual-monitor aware throughout (DP-1, DP-2)

## Usage

Clone and symlink or copy to `~/.config/hypr/`:

```bash
git clone https://github.com/Hexanchus29/dotfiles.git
cp -r dotfiles/* ~/.config/hypr/
```

Review `hyprland.conf` before applying, you will need to change paths and you will be able to change keybinds to your liking.
