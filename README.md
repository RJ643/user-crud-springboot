# User CRUD Spring Boot Project

A simple CRUD (Create, Read, Update, Delete) web application built with Spring Boot.

## 🚀 Features

- Create, Read, Update, Delete users
- RESTful API with JSON response
- Spring Boot 3.4.5 + Java 17
- Gradle build system

## 🛠️ Tech Stack

- Java 17
- Spring Boot 3.4.5
- Spring Web
- Spring Data JPA
- H2 (in-memory DB) or MySQL (optional)
- Gradle

## 📂 Project Structure

src ├── main │ ├── java │ │ └── com.example.usercrud │ │ ├── controller │ │ ├── model │ │ ├── repository │ │ └── service │ └── resources │ └── application.properties └── test

bash
복사
편집

## ✅ Getting Started

### Prerequisites

- JDK 17+
- Gradle (or use the included `gradlew`)
- Git

### Run locally

```bash
git clone https://github.com/RJ643/user-crud-springboot.git
cd user-crud-springboot
./gradlew bootRun
The server will start on: http://localhost:8080

📮 API Endpoints (예정)
Method	Endpoint	Description
GET	/api/users	Get all users
GET	/api/users/1	Get user by ID
POST	/api/users	Create a new user
PUT	/api/users/1	Update user
DELETE	/api/users/1	Delete user

🧑‍💻 Author
GitHub: @RJ643

📜 License
