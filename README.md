# API-CALL

## Student Name & Course
Diana Esguerra  
III - BSIT - B

---

## Project Description
API-CALL is a web-based RESTful API developed using Laravel.  
The project is designed to perform CRUD (Create, Read, Update, Delete) operations for managing student records efficiently. It uses JSON responses for data communication and supports API testing through Postman.

### Features
- Get All Students
- Get Single Student
- Add Student
- Update Student
- Partial Update Student
- Delete Student
- Delete All Students

---

## Technologies Used

- PHP
- Laravel 12
- MySQL / SQLite
- Eloquent ORM
- REST API
- Postman
- JSON

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Diana-dot-alt/api-call.git
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

## API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | /api/students | Get all students |
| POST | /api/students | Create a new student |
| GET | /api/students/{id} | Get a single student |
| PUT | /api/students/{id} | Update a student |
| PATCH | /api/students/{id} | Partially update a student |
| DELETE | /api/students/{id} | Delete a student |
| DELETE | /api/students | Delete all students |

---

## Screen Recording Demonstration

[Click here to view the screen recording demonstration]<br>
(https://drive.google.com/drive/folders/1gTHyfo8yNeKP45tiLngoN-e_HFSUorOp?usp=sharing)

---

## Note

This project is for educational purposes only.