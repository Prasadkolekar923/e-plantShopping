# e-plantShopping - Paradise Nursery

Welcome to **Paradise Nursery**, an online shopping application for plant lovers! This web application allows users to explore a variety of houseplants across multiple categories, view individual item details, add products to a shopping cart, and manage item quantities dynamically before checkout.

---

## 🌿 Project Overview

Paradise Nursery is designed to provide an intuitive, responsive, and seamless shopping experience for houseplant enthusiasts.

### Key Features
* **Landing Page:** Features a full-page background image, company name, overview paragraph ("About Us"), and a "Get Started" button to transition into the shopping experience.
* **Product Listing Page:** Displays at least six unique houseplants organized across three distinct categories. Each item includes a thumbnail image, plant name, price, and an "Add to Cart" button (which disables once the item is selected).
* **Interactive Navigation Header:** Included on both the Product Listing and Shopping Cart pages. Displays dynamic item counts on the shopping cart icon and provides quick navigation between pages.
* **Shopping Cart Page:** Displays selected items with unit prices, sub-totals, total cart cost, and total item count. Features quantity controls (increase/decrease), individual item deletion, a "Continue Shopping" button, and a "Checkout" button.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** React (Vite)
* **State Management:** Redux Toolkit (`CartSlice.jsx`)
* **Styling:** CSS3 (`App.css`)
* **Deployment:** GitHub Pages

---

## 📁 Repository Structure

```text
e-plantShopping/
├── public/
├── src/
│   ├── assets/
│   ├── AboutUs.jsx          # Company description and background component
│   ├── App.css             # Main styling including background images
│   ├── App.jsx             # Main application entry point & page navigation
│   ├── CartItem.jsx        # Shopping Cart component with quantity controls
│   ├── CartSlice.jsx       # Redux slice managing cart state
│   ├── ProductList.jsx     # Product display organized by categories
│   ├── main.jsx            # React root renderer with Redux Provider
│   └── store.js            # Redux store configuration
├── package.json
└── README.md
