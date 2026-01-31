# nightfox-btop

[Nightfox](https://github.com/EdenEast/nightfox.nvim) color schemes for [btop](https://github.com/aristocratos/btop).

## Themes

| Theme | Background |
|-------|------------|
| nightfox | Dark, blue-tinted |
| dayfox | Light, warm |
| dawnfox | Light, rose-tinted |
| duskfox | Dark, purple-tinted |
| nordfox | Dark, nord-inspired |
| terafox | Dark, teal-tinted |
| carbonfox | Dark, IBM Carbon-inspired |

## Installation

Copy the theme files to your btop themes directory:

```bash
# Linux/macOS
cp themes/*.theme ~/.config/btop/themes/

# Or clone and link
git clone https://github.com/yourusername/nightfox-btop.git
ln -s $(pwd)/nightfox-btop/themes/*.theme ~/.config/btop/themes/
```

Then select the theme in btop by pressing `Esc` → `Options` → `Color theme`.

## Preview

The themes use the official Nightfox color palettes with:
- Green → Yellow → Red gradients for CPU/temperature meters
- Blue → Purple → Red gradients for download graphs
- Green → Yellow → Orange gradients for upload graphs

## Credits

- [Nightfox.nvim](https://github.com/EdenEast/nightfox.nvim) by EdenEast
- [btop](https://github.com/aristocratos/btop) by aristocratos