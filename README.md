# GAME-HUB

A front-end e-commerce website for gaming furniture, PCs, peripherals, and room accessories. Built with HTML, CSS, and light vanilla JavaScript—no build step required.

## Features

- **Home** — Hero banner, category shortcuts, featured products, blog highlights, and newsletter signup
- **Products** — Full catalog with category tabs (computers, chairs, speakers, lighting, desks, accessories)
- **Sales** — Flash deals with countdown timer and promotional pricing
- **Blog** — Gaming setup articles and guides
- **Cart & wishlist** — Add/remove items and quantity controls (demo UI)
- **Login / register** — Auth forms with tab switching (demo, no backend)
- **Contact** — Store info and message form with success feedback

## Getting started

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.

No installation or server is required. For local development with live reload, you can use any static file server, for example:

```bash
npx serve .
```

## Project structure

```
GameHub-Website/
├── index.html          # Home page
├── products.html       # Product catalog
├── sales.html          # Sales & deals
├── blog.html           # Blog articles
├── cart.html           # Shopping cart
├── wishlist.html       # Saved items
├── login.html          # Login & registration
├── contact.html        # Contact form
├── style.css           # Global styles
├── images/             # Product and UI assets
└── README.md
```

## Tech stack

- HTML5
- CSS3 (responsive layout, `rem` scaling via `html { font-size: 62.5%; }`)
- [Font Awesome](https://fontawesome.com/) 6.2 (icons)
- [Google Fonts](https://fonts.google.com/) — Kenia, Mukta

## Pages overview

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Landing, categories, pricing highlights |
| Products | `products.html` | All shop items by category |
| Sales | `sales.html` | Discounted products |
| Blog | `blog.html` | Articles and tips |
| Cart | `cart.html` | Cart and order summary |
| Wishlist | `wishlist.html` | Saved products |
| Login | `login.html` | Sign in / create account |
| Contact | `contact.html` | Contact details and form |

## Responsive design

The site is optimized for desktop, tablet, and mobile widths:

- **≤1000px** — Navbar wraps; hero and pricing sections stack; product grids go to two columns.
- **≤700px** — Category cards and shop items use a single-column layout on narrow phones.
- **≤480px** — Compact navigation, typography, and full-width cards.

Open `index.html` and resize the browser (or use DevTools device mode) to preview breakpoints.

## Notes

- Checkout, search, and social login show placeholder alerts—there is no backend or payment integration.
- Product prices are illustrative and based on typical retail ranges for a UK-focused store.
- British English is used in customer-facing copy (e.g. *colour*, *enquiry*).

## Author

**Tai Odunaiya**

© Tai Odunaiya. All rights reserved.
