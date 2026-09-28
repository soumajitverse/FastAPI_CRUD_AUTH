# FastAPI Blog API

A simple Blog REST API built with **FastAPI**, **SQLAlchemy**, and **JWT authentication**.

## Features

* User signup and login
* Password hashing
* JWT-based authentication
* Create, read, update, and delete posts
* User–post relationship
* SQLAlchemy ORM
* Database integration

## Tech Stack

* Python
* FastAPI
* SQLAlchemy
* SQLite database
* JWT
* Uvicorn

## Run Locally

### 1. Create virtual environment

```bash
python -m venv venv
```

### 2. Activate it

Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the server

```bash
uvicorn main:app --reload
```

API will be available at:

```text
http://localhost:8000
```

Swagger documentation:

```text
http://localhost:8000/docs
```


## Project Status

This project is mainly built for **learning FastAPI, SQLAlchemy, authentication and CRUD operations**.
