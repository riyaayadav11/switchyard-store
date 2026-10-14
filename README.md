# Switchyard

A product listing page for a mechanical keyboard shop. One HTML file, no build step, no dependencies.

## Features

- 16 products across keyboards, switches, keycaps and accessories
- Search, category filter, switch feel filter, price slider and in-stock toggle
- Sorting by featured, newest, rating and price
- Quick view with a spec table for every product
- Wishlist and cart that are remembered between visits
- Free-shipping progress bar in the cart (over ₹5,000)
- Product pictures are drawn in code, so there are no image files to host
- Light and dark theme that follow the system setting
- Works on phones and desktops

## Run it

Open `index.html` in a browser. Checkout is not connected, so it is a front-end demo only.

## Make it your own

All products live in the `P` array near the top of the script. Change the names, prices and specs, or add new items. Each product picks a drawing style with the `art` field (`kb`, `sw`, `caps`, `artisan`, `cable`, `rest`, `mat`, `kit`).

## Ideas to extend it

- Load products from a JSON file or an API
- Add a product detail page and URL routing
- Connect a real backend for cart and orders
- Add pagination and a "compare" mode for keyboards
