# 🎬 Movie Server API

A modern, high-performance RESTful API for movie management, engineered with a focus on type-safety, scalability, and containerization.

## 🚀 Tech Stack
- [cite_start]**Runtime:** Node.js & Express [cite: 1, 22]
- [cite_start]**Language:** TypeScript [cite: 1, 33]
- [cite_start]**ORM:** DrizzleORM (Type-safe SQL) [cite: 1, 22]
- [cite_start]**Database:** PostgreSQL [cite: 1, 23]
- [cite_start]**Environment:** Docker & Docker Compose [cite: 1, 23]

## ✨ Key Features
- [cite_start]**Modern ORM Architecture:** Utilizing DrizzleORM for efficient and type-safe database interactions[cite: 1, 22].
- [cite_start]**Relational Data Modeling:** Optimized PostgreSQL schema design[cite: 1, 23].
- [cite_start]**Secure Authentication:** Implementation of auth systems for user protection and authorization[cite: 1, 24].
- [cite_start]**Containerized Deployment:** One-command setup using Docker to ensure environment consistency[cite: 1, 23, 25].

## 🛠️ Getting Started

### Prerequisites
- Docker & Docker Compose installed on your system.

### Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/HocTrinh-cmd/Movie-Server.git](https://github.com/HocTrinh-cmd/Movie-Server.git)
   cd Movie-Server
2. Launch with Docker Compose:

docker-compose up --build

3. Synchronize Database Schema (First-time setup):

docker exec -it movie-server npx drizzle-kit push

4. Seed Initial Data:

npx ts-node seedData.ts

📬 API Documentation
Explore and test the API endpoints using our Postman collection:

https://drive.google.com/file/d/1JFLzNpchVCu7WT5p7DsOgT-15hNuAoHX/view?usp=drive_link
