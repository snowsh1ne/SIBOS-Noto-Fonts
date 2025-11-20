# Fonts for SIBOS

This repository contains fonts used in SIBOS (Simple Image-based Operating System):

## Noto Emoji (Monochrome)
- **Purpose**: Emoji support for terminal emulators (xterm, st)
- **Format**: Variable font with monochrome outlines
- **File**: `noto-emoji/NotoEmoji-VariableFont_wght.ttf`
- **Static weights**: Available in `noto-emoji/static/` directory
- **Coverage**: All emoji characters as black/white outlines

## Google Sans Flex
- **Purpose**: Modern variable sans-serif font
- **Format**: Variable font with multiple axes (GRAD, ROND, opsz, slnt, wdth, wght)
- **File**: `google-sans-flex/GoogleSansFlex-VariableFont_GRAD,ROND,opsz,slnt,wdth,wght.ttf`

## License

Both fonts are licensed under the **SIL Open Font License, Version 1.1**

See individual LICENSE files in each font directory:
- `noto-emoji/OFL.txt`
- `google-sans-flex/OFL.txt`

## Source

Fonts downloaded from [Google Fonts](https://fonts.google.com/)

## Usage in SIBOS

These fonts are used in the SIBOS build system to provide comprehensive glyph coverage:
- Text rendering: Noto Sans, Noto Sans Mono
- Symbols: Noto Sans Symbols (arrows, Braille patterns)
- Emoji: Noto Emoji (monochrome for terminal compatibility)

For more information about SIBOS, visit: https://github.com/yourusername/SIBOS
