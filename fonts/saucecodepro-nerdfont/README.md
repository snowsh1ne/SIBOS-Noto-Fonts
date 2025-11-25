# SauceCodePro Nerd Font Mono

Nerd Fonts patched version of Adobe's Source Code Pro.
https://www.nerdfonts.com/

## Variants

### Full (for xterm/xst with fontconfig fallback)
- `SauceCodeProNerdFontMono-Regular.ttf`
- `SauceCodeProNerdFontMono-Bold.ttf`

These include format 12 cmap tables for full Unicode/emoji support.
Use with terminals that support fontconfig fallback chains.

### BMP-only (for zutty)
- `SauceCodeProNerdFontMonoBMP-Regular.ttf`
- `SauceCodeProNerdFontMonoBMP-Bold.ttf`

These have format 12 cmap tables stripped for compatibility with zutty,
which only supports the Basic Multilingual Plane (U+0000-U+FFFF).

Font family name changed to "SauceCodePro NFM BMP" to distinguish from full version.

All Nerd Font icons (U+E000-U+F8FF) are in BMP and work in both versions.

## Usage

zutty (use BMP version):
  zutty -font SauceCodeProNerdFontMonoBMP

xterm/xst (use full version):
  xterm -fa "SauceCodePro NFM" -fs 14
  xst -f "SauceCodePro NFM:size=14"

## License

SIL Open Font License - see OFL.txt
