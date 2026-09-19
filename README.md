# Flip&Co — production site

Clean production repository for the Flip&Co e-commerce experience.

## Structure
- HTML pages: storefront, catalog, product, checkout and legal pages
- `js/`: site shell, catalog, commerce, product and checkout logic
- `data/products.json`: product catalog
- `data/collections.json`: collection definitions
- `assets/`: production imagery and product artwork

## Deploy
Static site. No build step is required. Publish the repository root with GitHub Pages or another static host.

## Notes
The checkout currently collects an order request in the front-end flow; payment processing/backend order management are not included in this static repository.
