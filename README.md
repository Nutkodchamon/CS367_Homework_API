# Student API with Gin (Homework 4)

Simple RESTful Student Management API built with the :contentReference[oaicite:0]{index=0} framework and :contentReference[oaicite:1]{index=1} database using layered architecture.

## How to Run
```bash
go mod tidy
go run main.go

Server runs at:
http://localhost:8080

## 📁 Project Structure
```
go-api-gin/

─ main.go

─ models/        # Data models (structs)

─ handlers/      # HTTP request/response handling

─ services/      # Business logic layer

─ repositories/  # Database access (SQLite queries)

─ students.db

─ README.md
```

API Endpoints

GET /students

GET /students/:id

POST /students

PUT /students/:id

DELETE /students/:id

Validation

id and name required

gpa between 0.00–4.00

{ "error": "message" }

