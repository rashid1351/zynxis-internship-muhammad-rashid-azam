# Week 6 – Global State Management

## Frontend Development Internship

### Intern Information

**Name:** Muhammad Rashid Azam  
**Discipline:** Frontend Development  
**Week:** 6  
**Project:** SmartCart – Global State Management Shopping Application

---

## Project Overview

SmartCart is a modern e-commerce shopping cart application developed using React, TypeScript, and Redux Toolkit. The project demonstrates application-wide state management, persistent storage, reusable component architecture, and responsive UI design.

The application allows users to browse products, manage a shopping cart, customize preferences, and maintain their data across browser sessions using localStorage.

---

## Objectives

- Implement Global State Management using Redux Toolkit.
- Manage application-wide data efficiently.
- Persist state across browser refreshes.
- Create a scalable and maintainable architecture.
- Build a responsive and professional user interface.

---

## Features

### Product Catalog
- Browse products in a clean grid layout.
- Product cards with images, prices, and descriptions.
- Product detail view.

### Shopping Cart
- Add products to cart.
- Remove products from cart.
- Increase and decrease product quantities.
- Automatically calculate totals.
- Clear entire cart.

### User Preferences
- Dark Mode / Light Mode support.
- Currency preferences.
- Global preference management.

### Persistent Storage
- Cart data persists after page refresh.
- User preferences persist after page refresh.
- localStorage integration.

### State Management
- Redux Toolkit Store.
- Cart Slice.
- Preferences Slice.
- Centralized state management.

### Responsive Design
- Desktop-friendly layout.
- Tablet responsiveness.
- Mobile responsiveness.

---

## Technologies Used

- React
- TypeScript
- Redux Toolkit
- React Redux
- Vite
- Tailwind CSS
- Local Storage

---

## Project Structure

```text
src/
├── app/
├── assets/
├── components/
├── data/
├── features/
├── hooks/
├── lib/
├── routes/
├── utils/
├── router.tsx
├── routeTree.gen.ts
├── server.ts
├── start.ts
└── styles.css
```

---

## Redux Architecture

The application uses Redux Toolkit as a centralized state management solution.

### Cart Slice

Handles:

- cartItems
- totalQuantity
- totalAmount

Actions:

- addToCart
- removeFromCart
- increaseQuantity
- decreaseQuantity
- clearCart
- calculateTotals

### Preferences Slice

Handles:

- Theme Selection
- Currency Selection

Actions:

- toggleTheme
- changeCurrency

---

## Architecture & Logic Diagram

```text
Products Catalog
        │
        ▼
Add to Cart Action
        │
        ▼
Redux Store
        │
   ┌────┴────┐
   ▼         ▼
Cart Slice  Preferences Slice
   │              │
   ▼              ▼
UI Updates   localStorage
        │
        ▼
Persistent Data
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/week-6-global-state-management.git
```

Navigate to project directory:

```bash
cd week-6-global-state-management
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

---

## Build for Production

```bash
npm run build
```

---

## Learning Outcomes

Through this project, I learned:

- Global state management using Redux Toolkit.
- Managing application-wide data.
- State persistence using localStorage.
- Building scalable React applications.
- Creating reusable components.
- Responsive UI development.
- Organizing large-scale frontend projects.

---

## Deliverables

- Source Code
- Logic Diagram
- GitHub Repository
- README Documentation

---

## Author

### Muhammad Rashid Azam

Frontend Development Intern

GitHub: https://github.com/rashid1351

---

## Internship Program

Frontend Development Internship – Week 6

Topic: Global State Management using Redux Toolkit

