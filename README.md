# 📚 CodeBook Mock Server

Backend mock API for the **CodeBook application**.
This server provides a REST API for managing books, orders and users used by the CodeBook frontend.

The API is built using **JSON Server** and deployed on **Render** to simulate a real backend during development.

---

## 🌐 Live API

Base URL:

```
https://codebook-mock-server-hd47.onrender.com/
```

Example endpoints:

```
GET /books
GET /featured_books
GET /orders
GET /users
```

---

## ⚡ Features

📖 **Books API**
Fetch all books or individual book details.

🛒 **Orders Simulation**
Supports order data used by the frontend checkout flow.

⭐ **Featured Books Endpoint**
Returns curated book lists for homepage display.

👤 Users Endpoint
Simulates user data for login and registration.

🔍 **RESTful API Structure**
Supports common REST operations like:

* GET
* POST
* PUT
* DELETE

☁️ **Deployed on Render**
Accessible publicly for frontend integration.

⚡ **Fast Development Setup**
Uses JSON Server to quickly simulate backend APIs.

---

## 📡 API Endpoints

### Get All Books

```
GET /books
```

Example:

```
https://codebook-mock-server-hd47.onrender.com/books
```

---

### Get Book By ID

```
GET /books/:id
```

Example:

```
/books/1
```

---

### Featured Books

```
GET /featured_books
```

---

### Orders

```
GET /orders
POST /orders
```

---

## 🛠 Tech Stack

* **Node.js**
* **JSON Server**
* **Render (Deployment)**

---

## 🚀 Running Locally

Clone the repository:

```bash
git clone https://github.com/shital1223/codebook-mock-server.git
```

Navigate to the project:

```bash
cd codebook-mock-server
```

Install dependencies:

```bash
npm install
```

Start the mock server:

```bash
npx json-server --watch db.json --port 8000
```

Server will run at:

```
http://localhost:8000
```

---

## 📁 Project Structure

```
codebook-mock-server
│
├── db.json          # Mock database
├── package.json
└── README.md
```

---

## 🔗 Related Project

Frontend Application:

➡️ **CodeBook Frontend**
https://github.com/shital1223/Front-End-Projects/tree/main/React/codebook

