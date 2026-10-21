# i&Beyond — customer-facing storefront preview

Open `index.html` or publish this folder with GitHub Pages. The main customer-facing experience is a single-page site: home, shop catalogue, pre-owned, repairs, services, workspace and store location. `shop.html` redirects old bookmarks to the catalogue.

**Product cards now open a real product detail page** (`product.html?id=PRODUCT_ID`) instead of a modal popup. Each product page has a gallery, product description, price, stock/SKU information, option selector when available, contact action and a link back to the shop. The URL is shareable/bookmarkable and works on GitHub Pages without server-side routing.

Included catalogue data is a snapshot from 21 October 2026. Product stock is not live. The preview does not take payments or place orders; customers should contact the store to confirm availability.

Photos use the original iandbeyond.com image URLs where available. If a remote image fails, the interface tries another gallery image and then shows a clear fallback.

## Publish

Upload the contents of this ZIP to the root of the `psychic-telegram` repository, replacing the older files. Keep the `assets/` folder intact. Commit the changes and let GitHub Pages deploy. The main entry file remains `index.html`.
