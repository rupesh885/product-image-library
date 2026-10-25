# Product Image Library

Individual product image assets for the R&J Import Export catalog.

## Current verified status

- **64** product listings are tracked in `products.csv`.
- **51** products currently have separate image files in this repository.
- **12** images were imported from the existing `rupesh885/myImages` repository.
- **39** additional individual images were downloaded from image URLs already present in the supplied product catalog.
- **13** products remain pending and do not yet have an image file in this repository.
- No multi-product collage is used as an individual product asset.

Images imported from the existing repository and catalog URLs are identified as such in the `image_status` column. They are not represented as newly AI-generated images.

## Image requirements

- One image file per product.
- Filenames and paths are mapped by product ID in `products.csv`.
- Prefer a consistent square crop, clean background, and product-focused framing.
- Update the manifest only after the corresponding image file has been added and verified.

## Categories

- `Indian-Spices/`
- `Fresh-Fruits/`
- `Pulses-Grains/`
- `Fresh-Vegetables/`
- `Textiles-Garments/`
- `Industrial-Chemicals/`
- `Pharmaceutical-Drugs/`

## Key files

- [Product manifest](products.csv)
- [Image import workflow](.github/workflows/seed-existing-images.yml)
