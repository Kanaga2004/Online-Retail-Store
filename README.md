---

# 🛍️ Online Retail Store

A full-stack web application for an online retail store built using **Node.js**, **Express**, **EJS**, and **MySQL**. The application allows users to browse a product catalogue, view product details, manage a shopping cart, and register/login to their account.

---

## 🚀 Features

- 🗂️ View a catalogue of products from a MySQL database.
- 🔍 View detailed information for each product.
- 🛒 Add, update, or remove products from a shopping cart.
- 👤 User registration and login with password hashing (bcryptjs).
- 📊 Dynamic pages generated using EJS templates.
- 🗃️ Clean project structure with MVC architecture (Models, Views, Controllers).
- 📦 Session handling for shopping cart and user login.
- ⚙️ Admin-only features (e.g., view client list) *(if implemented)*.

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS (custom), EJS Templates
- **Database**: MySQL (with phpMyAdmin)
- **Authentication**: bcryptjs (password hashing)
- **Tools**: Nodemon, npm, Git

---

## 📂 Project Structure

```
Online-Retail-Store/
├── public/               # Static files (HTML, CSS, images)
├── views/                # EJS templates
├── db/                   # Database access modules
├── controllers/          # Request handling logic
├── services/             # Business logic
├── routes/               # Express routes
├── app.js                # Main server file
├── package.json          # Project metadata and dependencies
└── .gitignore
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Online-Retail-Store.git
   cd Online-Retail-Store
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up MySQL database**
   - Import the provided `sales.sql` file into your MySQL server.
   - Update database connection details in the project (e.g., in `db/dbQuery.js`).

4. **Run the development server**
   ```bash
   npm run dev
   ```
   Visit: `http://localhost:3000/`

---

## 📝 License

This project was developed as part of a web programming lab and is intended for educational purposes.

---

## 🙌 Acknowledgements

- Sales database and resources from [Lab3 Node.js Instructions](https://github.com/hbatatia/lab03-nodejs)
- Special thanks to the lab instructors and contributors.

---
