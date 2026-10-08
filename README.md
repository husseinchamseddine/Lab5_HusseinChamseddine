# Lab 5 - Postman and APIs

## Hussein Chamseddine

This project implements a Flask REST API connected to an SQLite database for user management.

## API Endpoints

- `GET /api/users` - Get all users
- `GET /api/users/<user_id>` - Get a user by ID
- `POST /api/users/add` - Add a user
- `PUT /api/users/update` - Update a user
- `DELETE /api/users/delete/<user_id>` - Delete a user

## How to Run

Install the required packages:

```bash
pip3 install flask flask-cors
python3 app.py
```
