# paper.kitty

A warm, café-inspired Kitty terminal theme with paper tones and rich mocha/coffee brown accents.

## Features

- 🌞 **Light mode** - Warm paper background with espresso brown text
- 🌙 **Dark mode** - Cozy dark roast with cream highlights
- ☕ Carefully crafted color palette inspired by café aesthetics
- 🎨 Perfect for all-day coding sessions
- 💫 Works beautifully with transparent backgrounds

## Preview

<div align="center">

### 🎨 Interactive Color Palettes

**[→ View Light Mode Palette](https://coolors.co/faf6f0-4a3728-b04c3f-6a7d3e-c47f2c-4d6c7d-8b5a5a-507964)** | **[→ View Dark Mode Palette](https://coolors.co/2a1f1a-e8dcc8-c85a4c-7a9048-c47f2c-4d6c7d-a36969-507964)**

### Light Mode Palette

| Color | Hex | Preview |
|-------|-----|---------|
| **Background** | `#faf6f0` | ![#faf6f0](https://img.shields.io/badge/Warm_Paper-faf6f0?style=for-the-badge&labelColor=4a3728) |
| **Foreground** | `#4a3728` | ![#4a3728](https://img.shields.io/badge/Dark_Roast-4a3728?style=for-the-badge&labelColor=faf6f0) |
| **Red** | `#b04c3f` | ![#b04c3f](https://img.shields.io/badge/Roasted_Berry-b04c3f?style=for-the-badge&labelColor=faf6f0) |
| **Green** | `#6a7d3e` | ![#6a7d3e](https://img.shields.io/badge/Matcha-6a7d3e?style=for-the-badge&labelColor=faf6f0) |
| **Yellow** | `#c47f2c` | ![#c47f2c](https://img.shields.io/badge/Honey-c47f2c?style=for-the-badge&labelColor=faf6f0) |
| **Blue** | `#4d6c7d` | ![#4d6c7d](https://img.shields.io/badge/Dusty_Denim-4d6c7d?style=for-the-badge&labelColor=faf6f0) |
| **Magenta** | `#8b5a5a` | ![#8b5a5a](https://img.shields.io/badge/Cocoa-8b5a5a?style=for-the-badge&labelColor=faf6f0) |
| **Cyan** | `#507964` | ![#507964](https://img.shields.io/badge/Mint-507964?style=for-the-badge&labelColor=faf6f0) |

### Dark Mode Palette

| Color | Hex | Preview |
|-------|-----|---------|
| **Background** | `#2a1f1a` | ![#2a1f1a](https://img.shields.io/badge/Dark_Roast-2a1f1a?style=for-the-badge&labelColor=e8dcc8) |
| **Foreground** | `#e8dcc8` | ![#e8dcc8](https://img.shields.io/badge/Cream-e8dcc8?style=for-the-badge&labelColor=2a1f1a) |
| **Red** | `#c85a4c` | ![#c85a4c](https://img.shields.io/badge/Cherry-c85a4c?style=for-the-badge&labelColor=2a1f1a) |
| **Green** | `#7a9048` | ![#7a9048](https://img.shields.io/badge/Matcha-7a9048?style=for-the-badge&labelColor=2a1f1a) |
| **Yellow** | `#c47f2c` | ![#c47f2c](https://img.shields.io/badge/Honey-c47f2c?style=for-the-badge&labelColor=2a1f1a) |
| **Blue** | `#4d6c7d` | ![#4d6c7d](https://img.shields.io/badge/Dusty_Denim-4d6c7d?style=for-the-badge&labelColor=2a1f1a) |
| **Magenta** | `#a36969` | ![#a36969](https://img.shields.io/badge/Mocha-a36969?style=for-the-badge&labelColor=2a1f1a) |
| **Cyan** | `#507964` | ![#507964](https://img.shields.io/badge/Mint-507964?style=for-the-badge&labelColor=2a1f1a) |

</div>

## Installation

### Quick Install

1. Clone or download the theme files:

```bash
curl -O https://raw.githubusercontent.com/saravenpi/paper.kitty/master/paper.conf
curl -O https://raw.githubusercontent.com/saravenpi/paper.kitty/master/paper-dark.conf
```

2. Move them to your Kitty themes directory:

```bash
mkdir -p ~/.config/kitty/themes
mv paper.conf ~/.config/kitty/themes/
mv paper-dark.conf ~/.config/kitty/themes/
```

### Manual Install

1. Copy the contents of `paper.conf` (light) or `paper-dark.conf` (dark)
2. Paste into your `~/.config/kitty/kitty.conf`

## Usage

### Option 1: Include the theme

Add to your `~/.config/kitty/kitty.conf`:

```conf
# Light mode
include themes/paper.conf

# OR Dark mode
include themes/paper-dark.conf
```

### Option 2: Direct configuration

Copy the color values from either theme file directly into your `kitty.conf`.

### Optional: Transparency

For that extra café vibe, add transparency:

```conf
background_opacity 0.85
background_blur 24
```

## Theme Files

- `paper.conf` - Light mode variant
- `paper-dark.conf` - Dark mode variant

## Related Projects

- [paper.nvim](https://github.com/saravenpi/paper.nvim) - Matching Neovim colorscheme
- [paper.tmux](https://github.com/saravenpi/paper.tmux) - Matching tmux theme

## License

MIT
