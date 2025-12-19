# 🏨 Hotel Management System

A full-stack **Hotel Booking and Management System** built using **Spring Boot** for the backend and **React.js** for the frontend. This project demonstrates how a real-world hotel management workflow can be implemented with a clean separation of concerns, RESTful APIs, and a modern UI.

The system is designed to handle hotel operations such as room management, bookings, and user interactions in a scalable and maintainable way.

---

## 🚀 Features

* Room listing and management
* Hotel booking workflow
* User-friendly React-based interface
* RESTful backend APIs
* Clean separation between frontend and backend
* Scalable project structure

---

## 🏗️ Tech Stack

### Frontend

* React.js
* JavaScript
* HTML5 & CSS3
* Axios for API communication

### Backend

* Spring Boot
* Java
* Spring REST
* JPA / Hibernate
* MySQL (or compatible relational database)

---

## 🧠 System Architecture

```
React Frontend
     ↓
Spring Boot REST API
     ↓
Database (MySQL)
```

The frontend communicates with the backend through REST APIs, while the backend handles business logic, data persistence, and validation.

---

## 📁 Project Structure

```
Hotel-Management-System/
├── frontend/        # React application
│   ├── src/
│   └── package.json
│
├── backend/         # Spring Boot application
│   ├── src/main/java/
│   ├── src/main/resources/
│   └── pom.xml
│
└── README.md
```

---

## 🧪 Running the Project Locally

### Backend Setup

1. Navigate to the backend directory

```bash
cd backend
```

2. Configure database credentials in `application.properties`

3. Run the Spring Boot application

```bash
mvn spring-boot:run
```

The backend will start on the configured port (default: `8080`).

---

### Frontend Setup

1. Navigate to the frontend directory

```bash
cd frontend
```

2. Install dependencies

```bash
npm install
```

3. Start the development server

```bash
npm start
```

The frontend will be available at `http://localhost:3000`.

---

## 🔐 Configuration

* Backend configuration is handled via `application.properties`
* Frontend API base URLs can be configured using environment variables

Make sure the frontend points to the correct backend URL during local development.

---


## 👤 Author

**Sujay HK**

* GitHub: [https://github.com/SUJAY-HK](https://github.com/SUJAY-HK)
* LinkedIn: [https://www.linkedin.com/in/sujay-hk](https://www.linkedin.com/in/sujay-hk)

---

This project is intended as a practical demonstration of full-stack development using **Spring Boot** and **React**, focusing on clean architecture and real-world applicability.
