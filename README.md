# Paradise Nursery Shopping Application

Welcome to **Paradise Nursery**, an e-commerce web application where plant enthusiasts can browse a diverse collection of houseplants, add them to a shopping cart, and manage item quantities seamlessly.

This project was built as part of the **Developing Front-End Apps with React** course by IBM Developer Skills Network on Coursera.

---

## 🌿 Project Overview

Paradise Nursery is designed to bring nature closer to everyday living spaces. Users can browse houseplants categorized by their benefits, view details including prices and descriptions, and easily manage their shopping cart with real-time price calculations.

---

## ✨ Features

### 1. Landing Page
* Welcoming greenhouse background imagery.
* Company title **"Paradise Nursery"** with tagline *"Where Green Meets Serenity"*.
* An **About Us** section detailing the company's mission and plant care expertise.
* A **"Get Started"** call-to-action button that transitions smoothly into the product catalog.

### 2. Product Listing Page
* Displays houseplants grouped into distinct categories:
  * Air Purifying Plants
  * Aromatic Fragrant Plants
  * Insect Repellent Plants
  * Medicinal Plants
  * Low Maintenance Plants
* Each plant card features:
  * High-quality thumbnail image
  * Plant name
  * Detailed description
  * Unit cost
  * **"Add to Cart"** button that updates dynamically to **"Added to Cart"** and disables itself once added.
* Persistent Navigation Bar with:
  * Company logo and link to Home
  * Link to Plants catalog
  * Shopping cart icon with a real-time badge showing the total number of items in the cart.

### 3. Shopping Cart Page
* Shows the total shopping cart amount dynamically calculated based on item quantities and prices.
* Displays each added plant with thumbnail, name, unit price, and subtotal.
* Interactive increment (`+`) and decrement (`-`) buttons to adjust quantities. Decrementing past 1 automatically prompts removal.
* A **Delete** button to remove specific items completely from the cart.
* A **"Continue Shopping"** button to return directly to the product catalog.
* A **"Checkout"** button notifying users with a "Coming Soon" prompt.

---

## 🛠️ Tech Stack

* **React** (v18)
* **Redux Toolkit** & **React-Redux** (for global cart state management)
* **Vite** (Next generation frontend build tool)
* **HTML5 & CSS3**

---

## 🚀 Getting Started

### Prerequisites
* [Node.js](https://nodejs.org/) (version 16 or higher)
* [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/onkargawade2005-maker/e-plantShopping.git
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

5. Open your browser and navigate to the local URL (usually `http://localhost:5173`).

---

## 📂 Project Structure

```
├── public/
├── src/
│   ├── assets/
│   ├── AboutUs.css         # Styling for AboutUs component
│   ├── AboutUs.jsx         # Company background & mission statement
│   ├── App.css             # Main application and landing page styles
│   ├── App.jsx             # Root component with landing page view
│   ├── CartItem.css        # Shopping cart view styles
│   ├── CartItem.jsx        # Shopping cart items & calculations component
│   ├── CartSlice.jsx       # Redux Toolkit slice for shopping cart
│   ├── index.css           # Global typography and base styles
│   ├── main.jsx            # Entry point with Redux Provider
│   ├── ProductList.css     # Product catalog and navbar styles
│   ├── ProductList.jsx     # Plant catalog & category showcase
│   └── store.js            # Redux store configuration
├── index.html
├── package.json
├── README.md
└── vite.config.js
```

---

## 📄 License

This project is licensed under the Apache-2.0 License.