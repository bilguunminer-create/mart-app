# US&K DTF Design Studio

Reusable project structure for the US&K DTF design catalog.

## Asset integrity

Original catalog artwork must be copied into `assets/original/` unchanged. Do not redraw, upscale, recolor, remove backgrounds, or overwrite originals. Working files and print exports belong in separate folders.

At project creation time, the referenced ChatGPT conversation exposed content-reference markers but no downloadable image files or Library attachments. Therefore the original artwork for MTW-001–MTW-020 is **not present in this project** and has not been invented.

## Contents

- `catalog/mtw-catalog.csv` — design ID register and asset status.
- `catalog/catalog-index.md` — human-readable catalog index.
- `workflow/order-workflow.md` — intake-to-delivery process.
- `standards/print-preparation.md` — DTF print-preparation rules.
- `assets/original/` — reserved for unchanged source artwork.
- `assets/working/` — editable production files; never treat as originals.
- `exports/` — approved print-ready files.

## Asset intake rule

When source files become available, place each original under `assets/original/` using its design ID, for example `MTW-001_original.ext`. Update the catalog row with the exact filename, format, dimensions, color mode, and checksum. If a source is still unavailable, leave the row marked `source_unavailable.`
