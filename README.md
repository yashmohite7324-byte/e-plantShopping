# Paradise Nursery Shopping Application

Paradise Nursery is an online plant shopping application built with React and Redux Toolkit. It allows plant enthusiasts to explore a curated catalog of houseplants, add plants to their shopping cart, manage item quantities, and review order totals seamlessly.

## Project Overview

Welcome to Paradise Nursery, where green meets serenity! This web application provides an intuitive e-commerce shopping experience for indoor plants, featuring:
- **Landing Page**: An attractive welcome page featuring company details, background imagery, and a "Get Started" call-to-action button.
- **Product Catalog**: A multi-category plant store showcasing over 30 unique houseplants categorized into:
  - Air Purifying Plants
  - Aromatic Fragrant Plants
  - Insect Repellent Plants
  - Medicinal Plants
  - Low Maintenance Plants
- **Interactive Shopping Cart**: Full Redux-powered state management to add items, dynamically update quantities, delete products, calculate item subtotals, and compute the total cart amount.
- **Dynamic Navigation Bar**: Persistent navigation displaying company branding, quick links between Plants and Cart, and a live cart badge indicating the total count of items.
- **Checkout Process**: Instant checkout feedback with notifications.

## Key Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile viewing.
- **State Management**: Powered by Redux Toolkit (`CartSlice`) with actions to add items (`addItem`), remove items (`removeItem`), and update quantities (`updateQuantity`).
- **Interactive Cart Controls**: Increase, decrease, or delete items directly from the cart view with real-time recalculation of unit costs and cart total amount.
- **Button State Tracking**: "Add to Cart" buttons dynamically update to "Added to Cart" and disable once an item is placed in the shopping cart.

## Technologies Used

- **React 18**: Component-based UI architecture.
- **Redux Toolkit & React-Redux**: Centralized state management for shopping cart operations.
- **Vite**: Modern frontend tooling and bundling.
- **CSS3**: Custom styles, responsive grid layouts, and transitions.

## Getting Started

### Prerequisites

- Node.js (version 16 or later)
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yashmohite7324-byte/e-plantShopping.git
   ```

2. Navigate into the project directory:
   ```bash
   cd e-plantShopping
   ```

3. Install project dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Build for production:
   ```bash
   npm run build
   ```

## License

This project is licensed under the Apache License 2.0.