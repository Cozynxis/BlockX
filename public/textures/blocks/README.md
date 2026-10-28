# BlockX block textures

The block-only palette uses 8 columns x 6 rows. The first two slots are reserved for `cobblestone` and `grass_side`; the remaining slots are transparent and available for future block textures. SVG sources are temporary, scalable asset masters; the engine can rasterize these to 32x32 or 64x64 PNG files later.

`atlas.svg` is a machine-friendly atlas (transparent empty cells). `palette-preview.svg` is a visual reference with an empty-slot grid. Grass top/bottom textures will be separate atlas entries when implemented.
