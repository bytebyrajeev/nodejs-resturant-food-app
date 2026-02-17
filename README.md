# 🍽️ Restaurant Food Ordering API

A scalable and modular **RESTful API** for a Restaurant Food Ordering Application built using **Node.js**, **Express.js**, and **MongoDB**.

This backend system provides APIs for managing users, restaurants, food items, and orders following clean architecture and best practices.

---

## 📌 Project Overview

This project serves as the backend for a restaurant/food ordering system. It allows:

- User Registration & Authentication  
- Restaurant Management  
- Food/Menu Management  
- Order Creation & Tracking  
- Secure API Handling with Middleware  

The application follows an MVC-based architecture for scalability and maintainability.

---

## 🚀 Features

- 🔐 JWT-based Authentication & Authorization  
- 👤 User Management System  
- 🏪 Restaurant CRUD Operations  
- 🍔 Food/Menu CRUD Operations  
- 🛒 Order Management System  
- ⚙️ Centralized Error Handling  
- 🌍 Environment-based Configuration  
- 📦 Modular Folder Structure  

---

## 🛠️ Tech Stack

- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JWT (JSON Web Token)  
- dotenv  

---

## 📂 Project Structure

```
├── controllers/       # Business logic
├── models/            # Database schemas
├── routes/            # API routes
├── middlewares/       # Custom middleware
├── config/            # Configuration files
├── server.js          # Entry point
└── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Create a .env file

Create a `.env` file in the root directory and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the server

```bash
npm run dev
```

or

```bash
npm start
```

Server will run at:

```
http://localhost:5000
```

---

## 📬 API Endpoints (Example)

### Auth Routes
- `POST /api/v1/auth/register`
- `POST /api/v1/auth/login`

### Restaurant Routes
- `POST /api/v1/restaurant/create`
- `GET /api/v1/restaurant/getAll`
- `PUT /api/v1/restaurant/update/:id`
- `DELETE /api/v1/restaurant/delete/:id`

### Food Routes
- `POST /api/v1/food/create`
- `GET /api/v1/food/getAll`
- `PUT /api/v1/food/update/:id`
- `DELETE /api/v1/food/delete/:id`

### Order Routes
- `POST /api/v1/order/create`
- `GET /api/v1/order/userOrders`

*Endpoints may vary depending on implementation.*

---

## 🧪 Testing

You can test APIs using:

- Postman  
- Thunder Client  
- cURL  

---

## 🔮 Future Improvements

- Payment Gateway Integration  
- Role-Based Access Control  
- Swagger API Documentation  
- Docker Deployment  
- Cloud Deployment (Render / Railway / AWS)  
- Unit & Integration Testing  

---

## 👨‍💻 Author

Rajeev Ranjan 

GitHub: https://github.com/bytebyrajeev

---

## 📄 License

This project is licensed under the MIT License.

If this project is based on another repository, please provide proper credit to the original author.
