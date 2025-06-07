# Amazon Clone Project

This project is a simple Amazon-like e-commerce web application built with vanilla JavaScript, HTML, and CSS. It demonstrates core e-commerce features such as product listing, cart management, checkout, and order tracking.

## Features
- **Product Listing:** Browse a grid of products with images, prices, and ratings.
- **Add to Cart:** Add products to the cart and select quantities.
- **Cart Management:** View, update, and remove items from the cart. Cart state is saved in localStorage.
- **Checkout:** Choose delivery options with dynamic delivery dates and shipping prices.
- **Order Tracking:** (Stub page) For future order tracking features.
- **Responsive Design:** Works on desktop and mobile devices.

## Project Structure
```
amazon.html           # Main product listing page
checkout.html         # Cart and checkout page
orders.html           # Orders page (stub)
tracking.html         # Tracking page (stub)
data/
  cart.js             # Cart state and logic
  products.js         # Product data
  deliveryOptions.js  # Delivery options and shipping prices
Script/
  amazon.js           # Product listing and add-to-cart logic
  checkout.js         # Cart rendering and checkout logic
  utils/
    money.js          # Currency formatting utility
styles/               # CSS files for layout and design
images/               # Product, icon, and logo images
```

## How to Run
1. Clone or download the project files.
2. Open `amazon.html` in your browser to start shopping.
3. Use the cart icon to view and manage your cart in `checkout.html`.

## Key Files
- **amazon.html:** Main entry point, displays products and cart icon.
- **Script/amazon.js:** Handles product rendering and add-to-cart actions.
- **Script/checkout.js:** Handles cart display, delivery options, and item removal.
- **data/cart.js:** Manages cart state and localStorage persistence.
- **data/deliveryOptions.js:** Contains available delivery options and prices.
- **Script/utils/money.js:** Formats prices for display.

## Dependencies
- [dayjs](https://day.js.org/) (for date calculations in checkout)
- No build tools or frameworks required; all code is vanilla JS and runs in the browser.

## Customization
- Add or edit products in `data/products.js`.
- Change delivery options in `data/deliveryOptions.js`.
- Update styles in the `styles/` directory.

---

This project is for educational/demo purposes and is not intended for production use.
