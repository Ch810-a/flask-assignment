# Flask Assignment

## Setup
pip install -r requirements.txt
python app.py

## Database Schema

CREATE DATABASE users;

CREATE TABLE users (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    email VARCHAR(100),
    role VARCHAR(50)
);

## SQL Queries Used

Insert:
INSERT INTO users (name, email, role) VALUES (...);

Retrieve All:
SELECT * FROM users;

Retrieve by ID:
SELECT * FROM users WHERE id = ?;

## Routes
/hello
/users
/new_user
/users/<id>