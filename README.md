# Vallore — TallowCraft (Shopify theme)

GitHub-ready Shopify theme for the Vallore / TallowCraft store. Standard 7-folder structure.

## Folders (put these at the ROOT of your GitHub repo)
- assets/     theme.css, theme.js
- config/     settings_schema.json, settings_data.json
- layout/     theme.liquid, password.liquid
- locales/    en.default.json
- sections/   announcement-bar, header, footer
- snippets/   stars, price
- templates/  index, product, collection, list-collections, page, cart, search, blog, article, 404, gift_card, password (.liquid)

## Page mapping (template file -> Shopify page) — Shopify assigns these automatically by filename
- index.liquid -> Home
- product.liquid -> Products
- collection.liquid -> Collections
- list-collections.liquid -> Collections list
- page.liquid -> Pages (also Contact, via the built-in contact form)
- cart.liquid -> Cart
- search.liquid -> Search
- blog.liquid -> Blogs
- article.liquid -> Blog posts
- 404.liquid -> 404
- gift_card.liquid -> Gift card
- password.liquid -> Password

## Connect to Shopify
1. Put these folders at the repo root (not inside a subfolder).
2. Shopify admin -> Online Store -> Themes -> Add theme -> Connect from GitHub -> pick the repo/branch.
3. Customize -> Publish.

## Setup
- Set your product's handle to `vallore-beef-tallow`, or change `product_handle` in
  Customize -> Theme settings. Give the product 1/2/3-jar variants and the buy box builds the tiers automatically.
