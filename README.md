# 🛍️ DemoRedux - Redux Toolkit E-Commerce Demo

A learning project built with **React**, **Redux Toolkit**, and **JSON Server** to demonstrate modern state management in a real-world e-commerce application. The project covers product management, user authentication, shopping cart functionality, routing, and CRUD operations while showcasing best practices for Redux Toolkit.

---

# ✨ Features

* 🛒 Browse products
* 📦 Product management (CRUD)
* 👤 User registration & login
* 🛍️ Shopping cart functionality
* ⚡ Global state management with Redux Toolkit
* 🌐 REST API integration using Axios
* 📱 Responsive UI with Tailwind CSS
* 🚀 Fast development using Vite
* 📝 Form handling with React Hook Form
* 🔄 Mock backend powered by JSON Server

---

# 🛠 Tech Stack

| Technology       | Purpose            |
| ---------------- | ------------------ |
| React 19         | Frontend Framework |
| Redux Toolkit    | State Management   |
| React Redux      | Redux Integration  |
| React Router DOM | Routing            |
| Axios            | API Requests       |
| React Hook Form  | Form Validation    |
| JSON Server      | Mock REST API      |
| Tailwind CSS     | Styling            |
| Vite             | Build Tool         |
| React Toastify   | Notifications      |

---

# 📂 Project Structure

```text
DemoRedux/
│
├── backend/
│   ├── db.json
│   └── package.json
│
├── ecommerce-prj/
│   ├── src/
│   │
│   ├── api/
│   │   └── axiosconfig.jsx
│   │
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Products.jsx
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   ├── admin/
│   │   │   ├── CreateProduct.jsx
│   │   │   └── UpdateProduct.jsx
│   │   └── user/
│   │       ├── Cart.jsx
│   │       ├── ProfileUser.jsx
│   │       ├── CreateUser.jsx
│   │       └── UpdateUser.jsx
│   │
│   ├── store/
│   │   ├── store.jsx
│   │   ├── ProductSlice.jsx
│   │   ├── UserSlice.jsx
│   │   └── UserActions.jsx
│   │
│   ├── App.jsx
│   └── main.jsx
│
└── README.md
```

---

# 🚀 Learning Objectives

This project demonstrates how to:

* Manage global state using Redux Toolkit
* Create Redux slices and actions
* Connect React components with Redux
* Perform CRUD operations
* Handle asynchronous API requests using Axios
* Build protected routes
* Manage shopping cart state
* Structure a scalable React application

---

# 📦 Features Overview

## 🛍️ Product Module

* Display products
* Create new products
* Update existing products
* Delete products

---

## 👤 User Module

* Register users
* Login users
* Update user profile
* Manage user information

---

## 🛒 Shopping Cart

* Add items to cart
* Remove items
* Update cart state
* Manage cart globally using Redux Toolkit

---

## ⚡ Redux Toolkit

The project demonstrates:

* Redux Store
* Slices
* Reducers
* Actions
* Async operations
* Global state management

---

# ⚙️ Installation

## Clone the repository

```bash
git clone https://github.com/su139t/DemoRedux.git
```

---

## Backend Setup

```bash
cd backend
npm install
npx json-server db.json
```

Backend runs at:

```text
http://localhost:3000
```

---

## Frontend Setup

```bash
cd ecommerce-prj
npm install
npm run dev
```

Open:

```text
http://localhost:5173
```

---

# 🔄 Project Workflow

```text
User
   │
   ▼
Login / Register
   │
   ▼
Redux Store
   │
   ├── Product Slice
   ├── User Slice
   └── Cart State
   │
   ▼
JSON Server API
   │
   ▼
UI Updates Automatically
```

---

# 📸 Screenshots

### 🏠 Home Page

> Add screenshot here

---

### 🛍️ Product Page

> Add screenshot here

---

### 🛒 Shopping Cart

> Add screenshot here

---

### 👤 User Authentication

> Add screenshot here

---

# 📚 Concepts Covered

* React Components
* Redux Toolkit
* React Redux
* Global State Management
* CRUD Operations
* React Router
* Axios
* JSON Server
* React Hook Form
* Tailwind CSS

---

# 🔮 Future Improvements

* 💳 Payment Gateway Integration
* ❤️ Wishlist
* 🔍 Product Search
* ⭐ Product Ratings
* 📦 Order Management
* 🔐 JWT Authentication
* ☁️ Express + MongoDB Backend
* 📧 Email Verification
* 🌙 Dark Mode
* 📱 Progressive Web App (PWA)

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch:

```bash
git checkout -b feature/NewFeature
```

3. Commit your changes:

```bash
git commit -m "Add New Feature"
```

4. Push your branch:

```bash
git push origin feature/NewFeature
```

5. Open a Pull Request.

---

# ⭐ Support

If this project helped you learn Redux Toolkit, consider giving it a ⭐ on GitHub.

---

# 👨‍💻 Author

**Sumit Birla**

GitHub: https://github.com/su139t

---

# 📄 License

This project is licensed under the MIT License.

---

## ❤️ Built with React, Redux Toolkit, Tailwind CSS & Vite
