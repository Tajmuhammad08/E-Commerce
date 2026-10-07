# ShopEase - E-Commerce Frontend Website

A responsive multi-page e-commerce website built with HTML5, CSS3 and vanilla JavaScript (no frameworks).

**Live Demo:** https://tajmuhammad08.github.io/E-Commerce/

## Features
- 7 responsive pages: Home, Shop, Product Detail, Cart, Account, Blog, Contact
- Shopping cart (add, update quantity, remove) saved in the browser using the localStorage API
- Real-time product search with a "no results" state
- Product detail page with image gallery, hover zoom, color selector and tabs
- Star rating and review form that updates the page without reloading (dynamic DOM rendering)
- Product slider using Glide.js
- Mobile-friendly layout with a modular CSS structure (base, layout, components, pages)

## Tech Stack
HTML5, CSS3, JavaScript (ES6 modules), localStorage API, Glide.js, Bootstrap Icons

## Folder Structure
```
index.html, shop.html, cart.html ...   pages
css/   base, layout, components, pages
js/    main, cart, search, product, single-product modules, data.json
img/   products, categories, slider, blogs
```

## Run Locally
Product data is loaded with `fetch()`, so open the project through a local server (not by double-clicking the file):
- VS Code: install "Live Server" extension, right-click `index.html` -> Open with Live Server
- or run `python -m http.server` in the project folder and open http://localhost:8000

## Future Improvements
- Backend and database integration
- User authentication and checkout
- Persist product reviews
