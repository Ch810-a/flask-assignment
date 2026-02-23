# Flask Assignment Project

## Objective
This project demonstrates a Flask-based web application with MySQL database integration and Git workflow implementation.

---

## Technologies Used
- Python 3
- Flask
- MySQL
- HTML
- Git & GitHub

---

## Project Setup

1. Clone the repository:
   git clone <your-repo-link>

2. Navigate to project folder:
   cd flask-assignment

3. Install dependencies:
   pip install -r requirements.txt

4. Run the application:
   python app.py

5. Open in browser:
   http://127.0.0.1:5000/

---

## Database Configuration

### Create Database
CREATE DATABASE users;

### Use Database
USE users;

### Create Table
CREATE TABLE users (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    email VARCHAR(100),
    role VARCHAR(50)
);

---

## SQL Queries Used

### Insert User
INSERT INTO users (name, email, role) VALUES ('Chetan', 'chetan@gmail.com', 'Admin');

### Retrieve All Users
SELECT * FROM users;

### Retrieve User By ID
SELECT * FROM users WHERE id = 1;

---

## Flask Routes

- /hello → Returns "Hello World!"
- /users → Displays all users in HTML table
- /new_user → Form to insert new user
- /users/<id> → View specific user details

---

## Git Workflow

- Initialized Git repository
- Created branch: assignment
- Implemented project features
- Created Pull Request
- Merged assignment branch into main

---

## Author
Chetan
