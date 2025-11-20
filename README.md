# SIBOS Noto Fonts

A curated collection of high-quality fonts for the SIBOS (Simple Image-based Operating System) project. This repository contains carefully selected fonts optimized for both terminal and graphical user interface usage.

## Overview

This repository maintains a clean, well-organized collection of fonts used in SIBOS. All fonts are sourced from [Google Fonts](https://fonts.google.com/) and are licensed under the SIL Open Font License (OFL).

## Repository Structure

```
SIBOS-Noto-Fonts/
├── README.md                    (this file)
├── .gitignore                   (git ignore rules)
└── fonts/                       (all font files)
    ├── README.md               (font-specific documentation)
    ├── noto-emoji/             (monochrome emoji font)
    │   ├── OFL.txt
    │   ├── README.txt
    │   ├── NotoEmoji-VariableFont_wght.ttf
    │   └── static/
    │       ├── NotoEmoji-Regular.ttf
    │       ├── NotoEmoji-Light.ttf
    │       └── ... (other weight variants)
    └── google-sans-flex/        (variable sans-serif font)
        ├── OFL.txt
        ├── README.txt
        └── GoogleSansFlex-VariableFont_GRAD,ROND,opsz,slnt,wdth,wght.ttf
```

## Fonts Included

### Noto Emoji (Monochrome)
- **Purpose**: Terminal-compatible emoji support
- **Format**: Variable font (TrueType)
- **License**: SIL Open Font License v1.1
- **Use Case**: System emoji rendering in terminal emulators (xterm, st)
- **Variants**: Variable weight + static weight options (Light, Regular, Medium, SemiBold, Bold)

### Google Sans Flex
- **Purpose**: Modern, flexible sans-serif typeface
- **Format**: Variable font with multiple axes
- **License**: SIL Open Font License v1.1
- **Design Axes**: GRAD, ROND, opsz, slnt, wdth, wght
- **Use Case**: UI text, headings, and general-purpose typography in SIBOS

## Usage

For detailed information about each font, see `fonts/README.md`.

To use these fonts in your SIBOS build:
1. Reference the font files from the appropriate subdirectory
2. Check the OFL.txt license in each font directory for licensing requirements
3. Ensure proper font fallback chains for comprehensive glyph coverage

## License

All fonts in this repository are licensed under the **SIL Open Font License, Version 1.1**.

Individual license files are provided in each font directory:
- `fonts/noto-emoji/OFL.txt`
- `fonts/google-sans-flex/OFL.txt`

You are free to use, modify, and distribute these fonts in accordance with the SIL OFL terms.

## Source

All fonts are downloaded from [Google Fonts](https://fonts.google.com/).

For more information about the SIBOS project, visit the main SIBOS repository.

## Maintenance

### Updating Fonts

When updating fonts:
1. Download the new font files from Google Fonts
2. Replace the font files in their respective directories
3. Update README files if needed
4. Commit changes with a clear message indicating the font version/date updated

### Directory Conventions

- Font directories use lowercase with hyphens (e.g., `noto-emoji`, `google-sans-flex`)
- Each font directory contains its own OFL.txt license file
- Font files retain their original names from Google Fonts

## Contributing

If you have suggestions for additional fonts or improvements to the collection, please refer to the main SIBOS project's contribution guidelines.
