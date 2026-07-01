<div align="center">

# 🏡 Livona

### A Modern Airbnb-inspired Property Rental Platform built with React, Express, MongoDB and Cloudinary.

<p align="center">
  <a href="https://livona-frontend.vercel.app">
    <img src="https://img.shields.io/badge/🌐_Live_Demo-Visit-success?style=for-the-badge">
  </a>
  <a href="https://github.com/rishabhprasad-12/Livona-Frontend">
    <img src="https://img.shields.io/badge/Frontend-Repository-61DAFB?style=for-the-badge&logo=react">
  </a>
  <a href="https://github.com/rishabhprasad-12/Livona-Backend">
    <img src="https://img.shields.io/badge/Backend-Repository-339933?style=for-the-badge&logo=node.js">
  </a>
</p>

<p align="center">

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-Frontend-646CFF?logo=vite&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-Backend-000000?logo=express)
![Node](https://img.shields.io/badge/Node.js-22-339933?logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb)
![Cloudinary](https://img.shields.io/badge/Cloudinary-Media-3448C5?logo=cloudinary)
![JWT](https://img.shields.io/badge/JWT-Authentication-black?logo=jsonwebtokens)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss)

</p>

---

> **Livona** is a modern full-stack property rental platform inspired by Airbnb. It enables users to discover, create, manage, review and save rental properties through an intuitive and responsive user experience.

</div>

---

# 📑 Table of Contents

- [📖 About](#-about)
- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [🏗 Project Architecture](#-project-architecture)
- [📂 Repository Structure](#-repository-structure)
- [🚀 Live Demo](#-live-demo)
- [📸 Screenshots](#-screenshots)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

# 📖 About

Livona is a full-stack property rental platform designed to provide a seamless experience for both property owners and travelers.

Users can:

- 🔍 Discover rental properties
- 🏡 Create and manage listings
- ☁ Upload optimized property images
- ❤️ Save favourite listings
- ⭐ Leave reviews and ratings
- 🔐 Securely authenticate using JWT

The project follows a modern MERN architecture with separate frontend and backend repositories for scalability and maintainability.

---

# ✨ Features

| Feature | Description |
|----------|-------------|
| 🔐 Secure Authentication | JWT-based login & registration with protected routes. |
| 🏡 Property Listings | Create, update, delete and browse rental properties. |
| ☁️ Cloudinary Integration | Optimized cloud image uploads with secure storage. |
| ❤️ Wishlist | Save favourite properties for future visits. |
| ⭐ Reviews & Ratings | Leave reviews and ratings for listings. |
| 🔍 Smart Search | Search listings by title, owner, location and country. |
| 🎯 Advanced Filters | Filter by category, rating and price. |
| 📱 Responsive UI | Optimized for Desktop, Tablet and Mobile. |
| ⚡ RESTful APIs | Clean and scalable backend architecture. |
| 🛡 Validation | Server-side validation using Joi. |
| 👤 Authorization | Only owners can edit or delete their listings. |

---

# 🛠 Tech Stack

## Frontend

| Technology | Purpose |
|------------|---------|
| React | UI Development |
| Vite | Build Tool |
| Tailwind CSS | Styling |
| Axios | API Communication |
| React Router | Routing |
| React Hot Toast | Notifications |

---

## Backend

| Technology | Purpose |
|------------|---------|
| Node.js | Runtime |
| Express.js | REST API |
| JWT | Authentication |
| bcrypt | Password Hashing |
| Joi | Validation |
| Multer | File Handling |
| Cloudinary | Image Storage |

---

## Database

| Technology | Purpose |
|------------|---------|
| MongoDB Atlas | Cloud Database |
| Mongoose | ODM |

---

## Deployment

| Platform | Purpose |
|----------|---------|
| Vercel | Frontend |
| Render | Backend |
| MongoDB Atlas | Database |
| Cloudinary | Image Hosting |

---

# 🏗 Project Architecture

```text
                     User
                       │
                       ▼
          React + Vite Frontend
                       │
                 Axios REST API
                       │
                       ▼
              Express.js Backend
           ┌─────────┼─────────┐
           ▼         ▼         ▼
     MongoDB Atlas  JWT   Cloudinary
           │                   │
      Users Listings       Images
      Reviews Wishlist
```

---

# 📂 Repository Structure

```
Livona
│
├── 📦 Livona-Frontend
│      React + Vite Frontend
│
└── 📦 Livona-Backend
       Express REST API
```

---

# 🚀 Live Demo

### 🌐 Frontend

https://livona-frontend.vercel.app

### ⚙ Backend API

https://livona-backend.onrender.com/api

---

# 📦 Repositories

### Main Repository

https://github.com/rishabhprasad-12/Livona

### Frontend

https://github.com/rishabhprasad-12/Livona-Frontend

### Backend

https://github.com/rishabhprasad-12/Livona-Backend

---

# 📸 Screenshots

> Screenshots coming soon...
<img width="1908" height="2832" alt="screencapture-livona-frontend-vercel-app-2026-07-01-08_45_24" src="https://github.com/user-attachments/assets/19e5748b-0f7f-427e-ae86-1cde991f7380" />

# 🚀 Getting Started

Follow the steps below to run Livona locally.

## 1️⃣ Clone Repositories

```bash
git clone https://github.com/rishabhprasad-12/Livona-Frontend.git

git clone https://github.com/rishabhprasad-12/Livona-Backend.git
```


## 2️⃣ Install Dependencies

### Frontend

```bash
cd Livona-Frontend

npm install
```

### Backend

```bash
cd Livona-Backend

npm install
```

---

## 3️⃣ Environment Variables

### Frontend (.env)

```env
VITE_API_URL=http://localhost:8080/api
```

---

### Backend (.env)

```env
PORT=8080

MONGO_URL=

JWT_SECRET=

CLOUD_NAME=

CLOUD_API_KEY=

CLOUD_API_SECRET=

FRONTEND_PROD_URL=http://localhost:5173
```

---

## 4️⃣ Start Development Server

### Backend

```bash
npm run dev
```

---

### Frontend

```bash
npm run dev
```

---

# ⚙ Project Workflow

```text
                 User
                   │
                   ▼
      React + Vite Frontend
                   │
          Axios HTTP Requests
                   │
                   ▼
          Express REST API
         ┌─────────┼──────────┐
         ▼         ▼          ▼
 Authentication MongoDB  Cloudinary
         │         │          │
         ▼         ▼          ▼
 Authorization Users      Images
             Listings
             Reviews
             Wishlist
```

---

# 🔄 Application Flow

### Authentication

```text
Register/Login

↓

JWT Generated

↓

Stored in LocalStorage

↓

Axios Interceptor

↓

Protected API Access
```

---

### Property Listing

```text
Create Listing

↓

Upload Image

↓

Cloudinary

↓

Store URL in MongoDB

↓

Display Listing
```

---

### Wishlist

```text
User

↓

Add Property

↓

Wishlist Collection

↓

Fetch Wishlist

↓

Display Saved Listings
```

---

### Reviews

```text
User

↓

Submit Review

↓

MongoDB

↓

Update Average Rating

↓

Display Latest Reviews
```

---

# 📂 Project Structure

```text
Livona

├── Livona-Frontend
│
│   ├── src
│   │
│   ├── components
│   ├── pages
│   ├── context
│   ├── layouts
│   ├── api
│   ├── utils
│   └── assets
│
└── Livona-Backend

    ├── controllers
    ├── middleware
    ├── models
    ├── routes
    ├── utils
    ├── validators
    └── app.js
```

---

# 🌍 Deployment

| Service | Platform |
|---------|----------|
| Frontend | Vercel |
| Backend | Render |
| Database | MongoDB Atlas |
| Image Storage | Cloudinary |

---

# 📚 Documentation

| Repository | Link |
|------------|------|
| Frontend | https://github.com/rishabhprasad-12/Livona-Frontend |
| Backend | https://github.com/rishabhprasad-12/Livona-Backend |

---

# 🛣 Roadmap

- [x] User Authentication
- [x] Property Listings
- [x] Cloudinary Image Upload
- [x] Wishlist
- [x] Reviews & Ratings
- [x] Search & Filters
- [x] Responsive Design
- [ ] Google Maps Integration
- [ ] Booking System
- [ ] Payment Gateway
- [ ] Admin Dashboard
- [ ] Chat System
- [ ] Notifications
- [ ] Email Verification
- [ ] OAuth Login

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve Livona:

1. Fork the repository

2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add AmazingFeature"
```

4. Push the branch

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

# 👨‍💻 Author

### Rishabh Shankar Prasad

GitHub

https://github.com/rishabhprasad-12

---

<div align="center">

### ⭐ If you like this project, consider giving it a Star!

Made with ❤️ using React, Express, MongoDB & Cloudinary.

</div>

