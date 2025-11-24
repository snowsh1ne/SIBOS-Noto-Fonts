# Noto Sans Mono - Fixed Metrics

Noto Sans Mono with corrected font metrics for proper monospace rendering.

## Fixes Applied

The original Noto Sans Mono has incorrect metadata that causes gaps in terminal emulators:

| Field | Original | Fixed |
|-------|----------|-------|
| hhea.advanceWidthMax | 1800 | 600 |
| post.isFixedPitch | 0 | 1 |
| OS/2.xAvgCharWidth | 632 | 600 |

## Source

Original fonts from: https://noto-website-2.storage.googleapis.com/pkgs/NotoSansMono-hinted.zip

Fixed using fonttools to correct width metadata.

## License

SIL Open Font License (OFL) - see OFL.txt
