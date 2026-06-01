# URL Shortener API

A simple URL shortener built with FastAPI and PostgreSQL.

## Getting Started

**Install dependencies**
pip install -r requirements.txt

**Run the server**
uvicorn main:app --reload

**Test the endpoints**
Visit http://127.0.0.1:8000/docs
or https://url-shortner-r6t4.onrender.com/docs

or https://url-shortner-r6t4.onrender.com/{the code generated } -> for redirect

## Endpoints

| Method | Endpoint | Description                              |
| ------ | -------- | ---------------------------------------- |
| POST   | /shorten | Submit a long URL, get a short code back |
| GET    | /{code}  | Redirects to the original URL            |

## Tech Stack

- FastAPI
- PostgreSQL (Neon) and render
- SQLAlchemy
