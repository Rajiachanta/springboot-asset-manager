# Personal Asset Manager (Backend)

Spring Boot backend to manage personal assets efficiently. Supports **CRUD operations**, **asset categories**, and **secure endpoints** with Spring Security and JWT authentication.

---

## Tech Stack

- **Backend**: Java 25, Spring Boot 3.5, Spring Security, Spring Data JPA, MySQL  
- **Authentication**: JWT with role-based access (`ROLE_USER`, `ROLE_ADMIN`)  
- **Others**: RESTful APIs, Swagger UI, Lombok

---

## Features

- Add, update, delete, and view assets  
- Categorize assets (Electronics, Furniture, etc.)  
- Secure endpoints with JWT & Spring Security  
- API documentation via Swagger UI  

---

## Setup Instructions

```bash
# Clone the repo
git clone https://github.com/Rajiachanta/springboot-asset-manager.git
cd springboot-asset-manager/backend

# Configure your MySQL database in application.properties
# Ensure the database exists (asset_manager)

# Run the backend
mvn spring-boot:run




