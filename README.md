# 🚗 EliteCars Sales and Rentals

EliteCars is a full-featured web application designed to streamline operations for car dealerships and rental businesses. It enables efficient **inventory management**, **sales tracking**, **rental scheduling**, and **financial reporting** through an intuitive interface built on modern web technologies.

---

## 📌 Project Overview

**EliteCars** offers a unified platform for managing both car sales and rentals. It simplifies customer interactions, optimizes vehicle availability, and automates business reporting. The system is ideal for dealerships, rental companies, and multi-branch automotive businesses.

---

## ✅ Features

- **Inventory Management**  
  Add, edit, and remove vehicle listings with attributes like make, model, year, mileage, and price.

- **Rental Scheduling**  
  Manage bookings, check vehicle availability, and set dynamic rental rates based on vehicle type and demand.

- **Sales Transactions**  
  Track customer inquiries, negotiate deals, and process car sales transactions efficiently.

- **Customer Profiles**  
  Maintain a centralized record of customer information to streamline service and support repeat business.

- **Financial Reporting**  
  Automatically generate reports for rental income, sales performance, and inventory valuation.

---

## 🛠️ Tech Stack

| Layer         | Technology                            |
|---------------|----------------------------------------|
| **Frontend**  | HTML, CSS, JavaScript, React.js        |
| **Backend**   | Node.js, Express.js                    |
| **Database**  | MySQL (via XAMPP & phpMyAdmin)         |
| **APIs**      | Payment Gateway Integration (Stripe/PayPal) |
| **DevOps**    | Docker, GitHub Actions (CI/CD)         |

---

## 🏁 Getting Started

### 📦 Prerequisites

- Node.js (v14+)
- XAMPP (for Apache & MySQL)
- Git
- Docker (optional for containerized deployment)

---

### 🚀 Setup Instructions

1. **Clone the Repository**
  
2. **Install Backend Dependencies**
-cd backend
-npm install

3. **Install Frontend Dependencies**
-cd ../frontend
-npm install

4. **Start XAMPP & Create MySQL Database**
-Launch XAMPP and start Apache & MySQL.
-Open http://localhost/phpmyadmin.
-Create a new database named elitecars_db.
-Import the provided .sql file from the /database folder.

5. **Configure Environment Variables**
-Create a .env file in the backend directory:
-DB_HOST=localhost
DB_USER=root
DB_PASSWORD=
DB_NAME=elitecars_db
PORT=5000

6. **Run the App**
-# In backend directory
npm start
-# In frontend directory
npm start

---
