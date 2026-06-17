# 🚀 Dynamic Product Catalog

A modern and responsive React application built to demonstrate **Dynamic UI & State Management** using React Hooks. This project allows users to search, filter, sort, and explore products in real-time while providing a clean and interactive user experience.

---

# 📌 Week 3: Dynamic UI & State

## Objective

Implement complex UI logic using **React Hooks (useState, useEffect)** and create a searchable product catalog with real-time filtering and sorting.

---

# ✨ Features

### 🔍 Real-Time Search

* Search products by name
* Instant search results while typing
* Case-insensitive search functionality

### 🎯 Category Filtering

Filter products by category:

* All
* Electronics
* Fashion
* Home
* Sports
* Books

### 📊 Product Sorting

Sort products dynamically using:

* Price: Low → High
* Price: High → Low
* Rating: High → Low
* Name: A → Z

### ⚡ React Hooks

Implemented using:

#### useState

* Products
* Search Query
* Selected Category
* Sort Option
* Loading State

#### useEffect

* Simulated API Data Fetching
* Product Loading Logic

### 📱 Responsive Design

Optimized for:

* Desktop (4 products per row)
* Tablet (2 products per row)
* Mobile (1 product per row)

### 🛍 Product Cards

Each product card includes:

* Product Image
* Product Name
* Category
* Price
* Rating Stars
* View Details Button

### ⏳ Loading State

Displays a loading spinner or message while products are being loaded.

### 😕 Empty State

Displays:

"No Products Found"

when no products match the selected search or filter criteria.

### ❤️ Bonus Features

* Product Details Modal
* Favorites System
* Dark Mode Toggle
* Smooth Animations
* Hover Effects

---

# 🛠 Technologies Used

* React.js
* JavaScript (ES6+)
* Vite
* CSS3
* React Hooks

---

# 📂 Project Structure

```bash
src/
│
├── components/
│   ├── ProductCard.jsx
│   ├── SearchBar.jsx
│   ├── CategoryFilter.jsx
│   ├── SortDropdown.jsx
│   ├── ProductModal.jsx
│   └── Loader.jsx
│
├── data/
│   └── products.js
│
├── hooks/
│   └── useProducts.js
│
├── pages/
│   └── ProductCatalog.jsx
│
├── styles/
│   └── catalog.css
│
├── App.jsx
└── main.jsx
```

---

# 📦 Product Data Example

```javascript
{
  id: 1,
  name: "Wireless Headphones",
  category: "Electronics",
  price: 4999,
  rating: 4.5,
  image: "/images/headphone.jpg",
  description: "Premium wireless headphones"
}
```

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/dynamic-product-catalog.git
```

Navigate to project directory:

```bash
cd dynamic-product-catalog
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

---

# 🔨 Build for Production

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

# 📋 Internship Requirements Covered

✅ Product Catalog with 20+ Products

✅ React Hooks (useState)

✅ React Hooks (useEffect)

✅ Real-Time Search

✅ Category Filtering

✅ Product Sorting

✅ Responsive Design

✅ Loading State

✅ Empty State

✅ Product Detail Modal

✅ Favorites Feature

✅ Clean Component Architecture

---

# 🌐 Deployment

This project can be deployed using:

* Vercel
* Netlify

---

# 👨‍💻 Author

**Muhammad Rashid Azam**

BS Information Technology (BSIT)
University of Education, DG Khan Campus

Frontend Development Internship – Week 3 Project

---

# 📜 License

This project is created for educational and internship purposes.

