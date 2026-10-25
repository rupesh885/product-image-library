# Product Image Library

A catalog of individual product image assets for the R&J Import Export product catalog.

## Current status

- **64** products tracked in `products.csv`.
- **12** individual product images have been imported from the existing `rupesh885/myImages` repository.
- **52** products still need their own image.
- Imported assets are marked `imported_existing`; they are existing files, not newly generated photos.
- The initial test upload was removed; the product folder now contains the imported image file for Lakadong Turmeric.

## Image policy

- One image file per product; do not use multi-product collages as product assets.
- Filenames and paths follow the product IDs in `products.csv`.
- Prefer 1200×1200 product photography with a clean background and consistent lighting.
- Update `image_status` in `products.csv` after each image has actually been added and verified.

## Categories

- `Indian-Spices/`
- `Fresh-Fruits/`
- `Pulses-Grains/`
- `Fresh-Vegetables/`
- `Textiles-Garments/`
- `Industrial-Chemicals/`
- `Pharmaceutical-Drugs/`

## Files

- [Product manifest](products.csv)
- [Import workflow](.github/workflows/seed-existing-images.yml)

The import workflow copied matching images that already existed in `myImages`. Continue creating and adding separate product images for the remaining manifest entries.
