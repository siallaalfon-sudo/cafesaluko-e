# Map Noodle Website

This repository contains a static, responsive implementation of the Map Noodle design (export-ready placeholder assets). Features included:

- Responsive static site (index.html, styles.css, script.js)
- Menu listing and ordering flow (add to cart, change qty, cart side-drawer)
- Cart persisted in localStorage
- Simple checkout form (static)

How to run locally

1. Clone the repository
2. Open `index.html` in your browser (or serve using a simple static server)

Note on assets

I was not able to programmatically fetch binary assets from the Figma page in this environment. Please export the images/icons from your Figma project and place them under the `/assets/` folder using these names (recommended):
- `logo.png` (site logo)
- `hero.jpg` (hero banner)
- `item-1.jpg`, `item-2.jpg`, `item-3.jpg`, ... (menu item images)

There is an `assets/README.txt` with instructions.

Customizing menu items

Menu items are defined in the HTML in the `section.menu` list as elements with `data-id`, `data-name`, `data-price`. You can edit or add items there.

GitHub Pages

This repo is configured to publish from the `main` branch (root). After the push, it may take a minute for Pages to build.