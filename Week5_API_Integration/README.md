# Live Data Dashboard

## Overview

Live Data Dashboard is a React-based web application that demonstrates API Consumption and Handling using a public REST API. The application fetches live product data, displays useful statistics, and provides advanced user interactions including search, filtering, sorting, loading states, empty states, and error handling.

This project was developed as part of the Frontend Development Internship – Week 5: API Consumption & Handling.

---

## Features

### API Integration

* Fetches live data from Fake Store API
* Uses asynchronous API requests
* Real-time data rendering

### Dashboard Statistics

* Total Products
* Total Categories
* Highest Price Product
* Average Product Price

### Product Catalog

* Responsive product cards
* Product images
* Product titles
* Categories
* Prices
* Ratings

### Search Functionality

* Search products by name
* Search products by category
* Instant filtering results

### Category Filtering

* View all categories
* Filter by specific category

### Sorting Options

* Price: Low to High
* Price: High to Low
* Name: A to Z
* Name: Z to A

### Loading State

* Skeleton loaders while fetching data
* Improved user experience

### Empty State

* Displays a friendly message when no products are available

### Error Handling

* Handles network failures
* Handles API response errors
* Retry functionality

### Responsive Design

* Mobile Friendly
* Tablet Friendly
* Desktop Friendly

---

## Technologies Used

* React.js
* Vite
* JavaScript (ES6+)
* Axios / Fetch API
* CSS3
* React Hooks

---

## API Used

Fake Store API

https://fakestoreapi.com/products

---

## Project Structure

```text
src/
│
├── components/
├── hooks/
├── services/
├── pages/
├── utils/
├── App.jsx
└── main.jsx
```

---

## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project directory

```bash
cd live-data-dashboard
```

3. Install dependencies

```bash
npm install
```

4. Run the development server

```bash
npm run dev
```

---

## Build for Production

```bash
npm run build
```

---

## Deployment

The application can be deployed on:

* Vercel
* Netlify

---

## Learning Outcomes

This project demonstrates:

* REST API Consumption
* React Hooks
* State Management
* Loading States
* Empty States
* Error Handling
* Component-Based Architecture
* Responsive UI Development

---

## Author

Muhammad Rashid Azam

Frontend Development Internship – Week 5
