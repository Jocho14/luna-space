
# Luna Space

Welcome to the **Luna Space**, a complete platform for managing and running an online furniture store. This app includes a client side for customers and an employee side for store staff, providing seamless functionalities for product management, purchasing, and payment.

[🌐 Visit the Live Website](https://luna-space.netlify.app)
---

## Project Overview

This app is divided into the following repositories, each serving a specific purpose:

1. **[furniture-store-ecommerce-ui](https://github.com/Jocho14/furniture-store-ecommerce-ui)**  
   _Frontend built with React.js._  
   - Client-side: Browse, search, add to favourites, share reviews and purchase furniture.
   - Employee-side: Manage products, inventory, and order tracking.

2. **[furniture-store-ecommerce-api](https://github.com/Jocho14/furniture-store-ecommerce-api)**  
   _Backend API built with NestJS._  
   - Handles authentication, authorization, and API endpoints for the frontend.
   - Provides CRUD operations for users, products, orders, and more.

3. **[furniture-store-ecommerce-stripe](https://github.com/Jocho14/furniture-store-ecommerce-stripe)**  
   _Payment server built with NestJS._  
   - Integrates with Stripe for secure payment processing.

4. **[furniture-store-ecommerce-db](https://github.com/Jocho14/furniture-store-ecommerce-db)**  
   _Database schemas for PostgreSQL._  
   - Includes table definitions and relationships.

---

## Features

### Client Side
- User registration and login.
- Browse furniture collections by category.
- Add items to cart and checkout with Stripe payment.
- Add furnitures to favourites.
- Share reviews.
- Search items.

### Employee Side
- Add, update, and delete products.
- Manage inventory levels and pricing.
- Process customer orders.

---

## Tech Stack

| Component              | Technology           |
|------------------------|----------------------|
| **Frontend**           | React.js, Scss, Tailwind CSS |
| **Backend API**        | NestJS, TypeORM, Jest      |
| **Payment Server**     | NestJS, Stripe API   |
| **Database**           | PostgreSQL, Firebase Storage |
| **Authentication**     | JWT        |
| **Deployment**         | Azure      |

---
