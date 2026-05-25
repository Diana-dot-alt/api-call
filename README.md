# Student Management API

## Athour & Course
Diana Esguerra
III - BSIT - B
---

## Project Title
Student Management API

---

## Project Description
Student Management API is a simple RESTful API built using Laravel.  
This project allows users to manage student records through CRUD operations (Create, Read, Update, Delete). It supports JSON responses and API testing using Postman.

Features:
- Get All Students
- Get Single Student
- Add Student
- Update Student
- Partial Update Student
- Delete Student
- Delete All Students

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Go to Project Directory

```bash
cd api-call
```

### 3. Install Dependencies

```bash
composer install
```

### 4. Configure Environment

Copy `.env.example` file to `.env`

```bash
cp .env.example .env
```

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Run Database Migration

```bash
php artisan migrate:fresh
```

### 7. Start Laravel Server

```bash
php artisan serve
```

### 8. Test API in Postman

Base URL:

```txt
http://127.0.0.1:8000/api
```

Example Endpoints:

```http
GET /students
GET /students/{id}
POST /students
PUT /students/{id}
PATCH /students/{id}
DELETE /students/{id}
DELETE /students
```