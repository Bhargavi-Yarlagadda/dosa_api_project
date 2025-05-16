# Dosa Restaurant REST API

This project provides a REST API backend for managing a dosa restaurant's orders, customers, and items using FastAPI and SQLite.

## Features

- Manage Customers: Add, update, view, and delete customer information.
- Manage Items: Add, update, view, and delete dosa menu items.
- Manage Orders: Add, update, view, and delete order information.
- Swagger UI: Automatically generated interactive API docs.
- SQLite Backend: Simple, file-based relational database with constraints.
- CRUD operations for customers, items, and orders
- JSON-based API requests and responses

## Technologies Used

- FastAPI for building the RESTful API
- SQLite for lightweight data storage
- Pydantic for request/response validation

## Project Setup

1. Install Required Libraries - pip install fastapi uvicorn
2. Run the following command to create and populate the database - python init_db.py
3. Run the API Server - uvicorn main:app --reload
4. Once the server is running, open the browser: Swagger Docs:
   - Interactive API docs: http://127.0.0.1:8000/docs
   - Raw OpenAPI Schema: http://127.0.0.1:8000/openapi.json
5. You can test all endpoints through the interactive Swagger UI available at: http://127.0.0.1:8000/docs


