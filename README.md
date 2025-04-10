# 🛒 Marketplace App

A full-stack marketplace application where users can sign up, log in, manage their products, browse categories, and edit profile settings.

## 🚀 Features

### 🔐 Authentication

- User Sign Up / Login
- JWT-based authentication
- Password hashing using `bcrypt`

### 🧑 User

- Profile page
- View user-specific products
- Edit user settings

### 🛍️ Marketplace

- Browse all listed products
- Filter products by categories
- Add, edit, delete your own products

---

## 🖥️ Frontend

### Built With:

- **React**
- **Tailwind CSS** for UI styling
- **React-hot-toast** for notifications
- **React Router** for routing

### Pages:

- `Login` / `Sign Up`
- `Marketplace` (main product listing)
- `Add Product`
- `Edit Product`
- `Delete Product`
- `Product Categories`
- `User Profile`
- `User Product List`
- `Settings`

---

## 🛠️ Backend

### Built With:

- **Express**
- **MongoDB / Mongoose**
- **JWT (jsonwebtoken)** for auth tokens
- **bcrypt** for password hashing
- **dotenv** for environment variables
- **cors** for cross-origin support
- **nodemon** for development

---

## 📦 Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/guboss3214/Marketplace.git
   cd Marketplace
   ```

2. **Frontend setup**

   ```bash
   cd frontend
   npm install
   npm run dev
   ```

3. **Backend setup**

   ```bash
   cd backend
   npm install
   npm run start
   ```

4. **Create a `.env` file in the backend directory**

   ```env
   PORT=3000
   FRONTEND_URL=http://localhost:5173
   CLOUDINARY_KEY=your_cloudinary_key
   CLOUDINARY_SECRET=your_cloudinary_secret
   CLOUDINARY_URL=your_cloudinary_url
   DB_PASSWORD=your_mongodb_password
   JWT_SECRET=your_secret_key
   DB_URL=your_mongodb_connection_string
   ```

5. **Create a `.env` file in the frontend directory**
   ```env
   VITE_BACKEND_URL=http://localhost:3000/api
   VITE_CLOUDINARY_URL=your_cloudinary_url
   ```

---

## 📌 Notes

- Ensure MongoDB is running locally or use a MongoDB Atlas URI.
- Protected routes require a valid JWT token.
- Toast notifications enhance UX feedback during actions.

---
