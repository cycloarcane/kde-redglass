# Red Glass — KDE Plasma Theme

A dark KDE Plasma theme in deep black and red glass tones. Translucent red accents over near-black surfaces with glassy window borders.

## Components

| Component | Description |
|---|---|
| **Plasma Desktop Theme** | Panel, widgets, popups, tooltips |
| **Aurorae Window Decoration** | Titlebar and window borders |
| **Color Scheme** | Application and Qt widget colours |

## Installation

### Via KDE System Settings (recommended)

1. **Plasma Desktop Theme** — System Settings → Appearance → Plasma Style → Get New → search "Red Glass"
2. **Window Decoration** — System Settings → Appearance → Window Decorations → Get New → search "Red Glass"
3. **Color Scheme** — System Settings → Appearance → Colors → Get New → search "Red Glass"

### Manual Installation

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/kde-redglass.git
cd kde-redglass

# Plasma desktop theme
mkdir -p ~/.local/share/plasma/desktoptheme/redglass
cp -r plasma-theme/* ~/.local/share/plasma/desktoptheme/redglass/

# Aurorae window decoration
mkdir -p ~/.local/share/aurorae/themes/redglass
cp -r aurorae/* ~/.local/share/aurorae/themes/redglass/

# Color scheme
cp color-scheme/RedGlass.colors ~/.local/share/color-schemes/
```

Then apply each component in System Settings → Appearance.

## Colour Palette

| Role | Value | Usage |
|---|---|---|
| Background (deepest) | `#190000` / `rgb(25,0,0)` | Buttons, base surfaces |
| Background (panels) | `#320000` / `rgb(50,0,0)` | Window backgrounds |
| Background (headers) | `#550000` / `rgb(85,0,0)` | Headers, tooltips |
| Accent / foreground | `#fd052c` / `rgb(253,5,44)` | Primary text, highlights |
| Selection background | `#350000` / `rgb(53,0,0)` | Selected items |
| Inactive text | `#cacaca` / `rgb(202,202,202)` | De-emphasised labels |
| Positive indicator | `#55ff7f` / `rgb(85,255,127)` | Success states |
| Negative indicator | `#ff5555` / `rgb(255,85,85)` | Error states |

## Compatibility

- KDE Plasma 6
- Aurorae window decoration engine

## License

GPL-2.0+ — see [LICENSE](plasma-theme/LICENSE)

## Author

Roan Caws — [cycloarcane](https://github.com/cycloarcane)

## Credits

Based on the **Black Glass** KDE theme by Mark Whittaker (phobian@tutanota.com).
Red Glass is a red-tinted recolour of the original Black Glass window decoration and plasma theme.
