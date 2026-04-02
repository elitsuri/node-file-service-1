# node-file-service

> Node File Service: File upload/download service with S3 integration and processing

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Node.js, TypeScript, Express, MySQL, Sequelize

## 🏗️ Architecture
Three-tier architecture: Node.js, TypeScript backend, React/TypeScript frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/node-file-service
cd node-file-service

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
