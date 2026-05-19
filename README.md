# Wallpaper Collection

Wallpaper and terminal image assets for the `anto426` Arch/Hyprland setup.

## Structure

```text
.
├── Wallpapers/  # Desktop wallpapers copied to ~/Pictures/Wallpapers
└── neofetch/    # Fastfetch logos copied to ~/Pictures/neofetch
```

These assets are consumed by:

- [`Arch-Hyprland`](https://github.com/Anto426/Arch-Hyprland)
- [`auto-setup-LT`](https://github.com/Anto426/auto-setup-LT)
- [`dotfiles`](https://github.com/Anto426/dotfiles)

The dotfiles sync config can also point to a Google Drive or local sync folder with the same directory names:

```bash
export ANTO426_REMOTE_ASSETS_DIR="$HOME/Google Drive/anto426"
export ANTO426_NEOFETCH_DIR="$HOME/Pictures/neofetch"
```
