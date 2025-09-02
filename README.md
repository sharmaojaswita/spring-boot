# 🚀 Spring Boot Project
Spring Boot + Spring AI CRUD API | Aug 2025

Built a RESTful CRUD API using Spring Boot and Spring Data JPA, integrated with PostgreSQL for persistent storage.

Implemented service and repository layers for clean business logic and database operations.

Enhanced functionality with Spring AI, dynamically generating personalized learning path recommendations based on user inputs.

Tested endpoints using IntelliJ HTTP Client, with proper error handling via ResponseEntity.

Tech Skills: Java, Spring Boot, Spring Data JPA, Spring AI, PostgreSQL, REST API, IntelliJ IDEA, JSON


---

## 📌 Features
- REST API endpoints for `SoftwareEngineer`
- Create, Read, Update, Delete operations
- Example HTTP requests included (`API Requests.http`)
- Configurable with `application.properties`
- Docker support via `docker-compose.yml`

---

## 🛠️ Tech Stack
- **Java 17+**
- **Spring Boot**
- **Spring Data JPA**
- **PostgreSQL** (or other databases)
- **Docker & Docker Compose**

---

## 📂 Project Structure
```

spring-boot/
│── src/main/java/...   # Application source code
│   ├── Application.java
│   ├── AiService.java
│   ├── SoftwareEngineerRepository.java
│── src/main/resources/
│   ├── application.properties
│── pom.xml             # Maven dependencies
│── docker-compose.yml  # Docker configuration
│── API Requests.http   # Sample API requests

````

---

## ▶️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/sharmaojaswita/spring-boot.git
cd spring-boot
````

### 2. Build & Run

Using Maven:

```bash
./mvnw spring-boot:run
```

Or with Docker:

```bash
docker-compose up --build
```

### 3. Test the API

The application runs on `http://localhost:8080`.

Example endpoints:

* `GET /api/v1/software-engineers`
* `GET /api/v1/software-engineers/{id}`
* `POST /api/v1/software-engineers`
* `PUT /api/v1/software-engineers/{id}`
* `DELETE /api/v1/software-engineers/{id}`

---

## 📖 Example Request (PUT)

```http
PUT http://localhost:8080/api/v1/software-engineers/1
Content-Type: application/json

{
  "name": "Alice Johnson Updated",
  "techStack": "Java, Spring Boot, Docker",
  "LearningPathRecommendation": "Master Docker & Kubernetes"
}
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Added feature"`)
4. Push branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

````

---

👉 After adding it, just run:
```bash
git add README.md
git commit -m "Added README"
git push

🏆 Certification

Built as part of Spring Boot for Beginners (Amigoscode)
https://amigoscode.com/certificates/2ef736bf-b5bb-4026-b0c8-a50ce7be47b6

