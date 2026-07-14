# e-plantShopping

**Paradise Nursery** — a React + Redux shopping application for browsing and buying houseplants.

## Overview

`e-plantShopping` is the front end of the **Paradise Nursery** shopping application. It lets users browse a curated collection of houseplants, add them to a shopping cart, and manage their selections before checkout.

The application is built with **React** for the user interface and **Redux Toolkit** for global cart state management. It is deployed using **GitHub Pages**.

## Features

The app is organized into three main pages:

- **Landing Page** — A welcoming page with a background image, the company name, a short paragraph about Paradise Nursery, and a *Get Started* button that leads to the product listing.
- **Product Listing Page** — Displays at least six unique houseplants grouped into three or more categories. Each plant shows a thumbnail, name, and price, along with an *Add to Cart* button that disables once the item is added. A header with a live cart-item counter and navigation links appears on this page.
- **Shopping Cart Page** — Shows every plant added to the cart with its thumbnail, name, and unit price. Users can increase or decrease the quantity of each item, delete items, and see the total number of plants and the total cost. It also includes *Continue Shopping* and *Checkout* buttons.

## Tech Stack

- **React** — component-based UI
- **Redux Toolkit** — cart state management (`CartSlice`)
- **CSS** — styling and layout
- **GitHub Pages** — deployment

## Getting Started

```bash
# Clone the repository
git clone https://github.com/<your-username>/e-plantShopping.git

# Move into the project directory
cd e-plantShopping

# Install dependencies
npm install

# Run the development server
npm run dev
```

## Project Structure

| File | Purpose |
|------|---------|
| `App.jsx` | Landing page with company name and *Get Started* button |
| `App.css` | Styling, including the landing page background image |
| `AboutUs.jsx` | Company description |
| `ProductList.jsx` | Product listing page with categorized plants |
| `CartItem.jsx` | Shopping cart page and item controls |
| `CartSlice.jsx` | Redux slice managing cart state |

## Deployment

The application is deployed with GitHub Pages. Once built, the live version can be accessed through the repository's GitHub Pages URL.
