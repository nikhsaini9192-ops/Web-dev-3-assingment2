# Student Management REST API

A simple **REST API** built using **Node.js** and **Express.js** for managing student records. This project was created as **Web Development III (Unit-2) Lab Assignment**.

## Features

* Create Express Server
* Student CRUD Operations
* Custom Logger Middleware
* Modular Routing
* Proper Error Handling
* REST API Testing with Postman

## Tech Stack

* Node.js
* Express.js
* Postman

## Project Structure

student-management-rest-api/
│
├── data/
│ └── students.js
├── middleware/
│ └── logger.js
├── routes/
│ └── studentRoutes.js
├── app.js
├── package.json
└── README.md

## Installation

1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

2. Open the project folder

```bash
cd student-management-rest-api
```

3. Install dependencies

```bash
npm install
```

4. Start the server

```bash
node app.js
```

Server runs at:

```text
http://localhost:3000
```

## API Endpoints

| Method | Endpoint        | Description       |
| ------ | --------------- | ----------------- |
| GET    | `/students`     | Get all students  |
| GET    | `/students/:id` | Get student by ID |
| POST   | `/students`     | Add new student   |
| PUT    | `/students/:id` | Update student    |
| DELETE | `/students/:id` | Delete student    |

## Example Student Data

```json
{
  "id": 1,
  "name": "Rahul",
  "age": 20,
  "course": "BCA"
}
```

## HTTP Status Codes

* **200** – Success
* **201** – Created
* **400** – Bad Request
* **404** – Not Found

## Testing

All APIs were tested successfully using **Postman**.

## Assignment Requirements Completed

* Express Server
* CRUD APIs
* Logger Middleware
* Modular Routing
* Error Handling
* Postman Testing

## Author

**Nikhil **
BCA (AI & Data Science)
