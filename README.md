
# 👤 UserBoard - User Management App (CRUD)

A simple full-stack CRUD application built with **Node.js**, **Express**, **MongoDB**, and **EJS** for managing user data.

---

## 🚀 Features

- ✅ Create new users with name, email, and image URL
- 📄 View all users
- ✏️ Edit/update user details
- ❌ Delete users
- 💅 Styled with Tailwind CSS

---

## 🔧 Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS (Embedded JavaScript Templates)
- **Database**: MongoDB with Mongoose
- **Styling**: Tailwind CSS

---

## 📁 Project Structure

```
userboard/
├── models/
│   └── user.js
├── public/
│   └── stylesheets/
│       └── style.css
├── views/
│   ├── index.ejs
│   ├── read.ejs
│   └── edit.ejs
├── app.js
├── package.json
└── README.md
```

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/userboard.git
   cd userboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start MongoDB**
   - Ensure MongoDB is installed and running

4. **Run the app**
   ```bash
   node app.js
   ```

5. **Open in browser**
   ```
   http://localhost:3001
   ```

---

## 🌐 Routes Overview

| Method | Route             | Description             |
|--------|-------------------|-------------------------|
| GET    | `/`               | Create user form        |
| POST   | `/create`         | Submit new user         |
| GET    | `/read`           | View all users          |
| GET    | `/edit/:userid`   | Show update form        |
| POST   | `/update/:userid` | Update user details     |
| GET    | `/delete/:id`     | Delete user             |

---

## 🖼️ Screenshot

> Replace the link below with your own screenshot or GitHub image  
![Preview](https://via.placeholder.com/800x400?text=User+CRUD+App+UI)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [EJS](https://ejs.co/)
- [Tailwind CSS](https://tailwindcss.com/)
