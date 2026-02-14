🚀 BOOKWORM.COM
📚 Full-Stack E-Book Management & Rental System

A secure, scalable, and containerized full-stack web application for managing an online e-book store with purchase, rental, and royalty tracking capabilities.

🧠 Project Overview

BOOKWORM.COM is a full-stack web application designed to simulate a real-world digital bookstore platform.

It enables users to:

Browse e-books

Purchase or rent books

Manage their digital library

Access content with time-based controls

The system ensures secure authentication, clean API architecture, and automated royalty calculations for authors.

✨ Core Features
🔐 Secure Authentication & Authorization

JWT-based authentication

Spring Security integration

Role-based access (Admin / User)

Protected REST endpoints

📚 E-Book Management (Admin)

Add / Update / Delete books

Manage categories

Set pricing & rental duration

Maintain inventory records

🛒 Purchase & Rental System

E-book purchase functionality

Rental with expiration control

Personal digital library

Transaction history tracking

💰 Automated Royalty System

Author royalty calculation

Revenue tracking per transaction

Automated royalty distribution logic

📦 Dockerized Deployment

Backend containerization

MySQL container support

Easy local deployment setup

Production-ready configuration

🛠️ Tech Stack
🎨 Frontend

React.js

JavaScript

HTML5

CSS3

Axios

React Router

⚙️ Backend

Java 17

Spring Boot 3

Spring Security

JWT Authentication

REST APIs

JPA (Hibernate)

Maven 3

🗄️ Database

MySQL 8

Structured relational schema

Transaction & royalty tracking

🧩 Additional Module

.NET Core 8.0

Entity Framework

🏗️ System Architecture

The project follows a Layered Architecture Pattern:

Controller Layer
        ↓
Service Layer
        ↓
Repository Layer (JPA)
        ↓
MySQL Database

✅ Benefits:

Clean separation of concerns

Scalable backend structure

Secure API communication

Easy maintainability & testing

📁 Project Structure
BOOKWORM.COM/
│
├── BOOKWORM_PRO/                  # Spring Boot Backend
├── BookWormNET/                   # .NET Core Backend Module
├── frontend-updated_29morning/    # React Frontend
│
└── README.md

🔄 Application Workflow

1️⃣ User registers / logs in (JWT authentication)
2️⃣ User browses available books
3️⃣ User purchases or rents an e-book
4️⃣ Transaction is recorded
5️⃣ Royalty is calculated automatically
6️⃣ Book is added to digital library
7️⃣ Rental expires automatically (if rented)

⚙️ Running the Project Locally
1️⃣ Clone Repository
git clone https://github.com/Adarsh11Sharma/BOOKWORM.COM.git
cd BOOKWORM.COM

2️⃣ Setup Database

Create MySQL database

Update application.properties with credentials

3️⃣ Run Spring Boot Backend
cd BOOKWORM_PRO
mvn spring-boot:run


Backend runs on:

http://localhost:8080

4️⃣ Run React Frontend
cd frontend-updated_29morning
npm install
npm run dev


Frontend runs on:

http://localhost:5173

5️⃣ Run with Docker (Optional)
docker-compose up --build

🔐 Security Highlights

JWT token authentication

Encrypted password storage

Role-based access control

Protected REST APIs

Axios interceptor for token handling

🚀 Future Enhancements

Payment gateway integration

Advanced analytics dashboard

Cloud deployment (AWS / Azure)

Microservices migration

Recommendation engine

Email notifications

👨‍💻 Author

Adarsh Sharma
Full Stack Developer

🔗 GitHub:
https://github.com/Adarsh11Sharma

Contact no: 8421505681

⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
