# Data Science Assignment 1 – Version C Datasets

This repository contains scraped datasets prepared for **Data Science Assignment 1 – Version C**:

- Complete **PokéMart product catalog** (static pages)
- Dynamically loaded **TechBazaar customer testimonials** (infinite scroll batches)

## Files

### `/home/runner/work/Datasets/Datasets/23L_0647_versionC_static_products.csv`
Scraped product catalog data from PokéMart.

Columns:
- `product_name`
- `price`
- `sku`
- `stock`
- `categories`
- `tags`
- `short_description`
- `product_url`
- `listing_page`

### `/home/runner/work/Datasets/Datasets/23L_0647_versionC_dynamic_testimonials.csv`
Scraped customer testimonials from TechBazaar loaded dynamically while scrolling.

Columns:
- `testimonial_text`
- `rating`
- `scroll_batch`

## Notes

- CSV files include headers in the first row.
- `listing_page` indicates the source pagination page for each product.
- `scroll_batch` indicates the scroll/load batch where each testimonial was captured.
