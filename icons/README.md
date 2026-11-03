# PIXEL LENORMAND icons

These icons use the original, unmodified lily card artwork (No. 30) drawn
in `../lenormand_sprites.png`. No generated or redrawn artwork is used.

`icon-source.png` is the exact 64 × 64 pixel tile at x=320, y=256 in the
384 × 384 sprite sheet (row 5, column 6, counting from 1).
Original colors and transparency are preserved; no background is added.

- `icon-source.png`: exact original 64 × 64 tile
- `icon-512.png`, `icon-192.png`: application icons
- `icon-180.png`: Apple touch icon size
- `icon-16.png`, `icon-32.png`, `icon-48.png`: small PNG icons
- `favicon.ico`: 16, 32 and 48 pixel images in one ICO file

All sizes use nearest-neighbor resampling, without smoothing. Small sizes
necessarily sample fewer source pixels; the original tile is retained above.
These files are intentionally not linked or embedded in HTML. The ICO stays
in this directory to avoid automatic root `/favicon.ico` discovery.
