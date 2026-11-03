# PIXEL LENORMAND card icons

The original lily (card 30) is presented in a cream card with an antique-gold
border, card number and LILY label on a forest-green background.
The flower itself is not generated, redrawn, recolored or smoothed.

- `lily-original.png`: exact 64 × 64 tile at x=320, y=256 in
  `../lenormand_sprites.png` (row 5, column 6)
- `icon-source.png`: 512 × 512 card composition; the original tile is enlarged
  five times with nearest-neighbor resampling and placed at x=92, y=96
- `icon-512.png`, `icon-192.png`: application icons
- `icon-180.png`: Apple touch icon size
- `icon-16.png`, `icon-32.png`, `icon-48.png`: small PNG icons
- `favicon.ico`: 16, 32 and 48 pixel images in one ICO file

Resized outputs use nearest-neighbor resampling. Small favicon sizes simplify
the fine details by sampling; the full original artwork is retained above.
No files are linked or embedded in HTML. The ICO stays in this directory to
avoid automatic root `/favicon.ico` discovery.
