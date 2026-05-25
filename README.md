# Student Management API

Student Management API is a simple RESTful API built using Laravel.  
This project is designed to manage student records through CRUD operations using JSON responses.

This project is intended for educational purposes only.

---

# Features

- Get All Students
- Get Single Student
- Add Student
- Update Student
- Partial Update Student
- Delete Single Student
- Delete All Students

---

# Technologies Used

- Laravel 12
- PHP
- SQLite / MySQL
- Postman
- REST API

---

# Installation

## Clone Repository

```bash
git clone <repository-url>
Go to Project Folder
cd api-call
Install Dependencies
composer install
Configure Environment

Copy .env.example to .env

cp .env.example .env
Generate Application Key
php artisan key:generate
Run Migration
php artisan migrate:fresh
Start Server
php artisan serve
Base URL
http://127.0.0.1:8000/api
API Endpoints
GET All Students
GET /students
GET Single Student
GET /students/{id}
POST Create Student
POST /students
Request Body
{
  "name": "Diana",
  "email": "diana@gmail.com",
  "course": "BSIT"
}
PUT Update Student
PUT /students/{id}
PATCH Partial Update
PATCH /students/{id}
DELETE Single Student
DELETE /students/{id}
DELETE All Students
DELETE /students
Sample Response
[
  {
    "id": 1,
    "name": "Diana",
    "email": "diana@gmail.com",
    "course": "BSIT"
  }
]
Author

Diana Esguerra

License

This project is for educational purposes only.