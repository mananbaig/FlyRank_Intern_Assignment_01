# Minimal FastAPI Backend

This project is a very small FastAPI application with two simple GET endpoints.

## Project structure

```text
.
├── main.py
├── requirements.txt
└── README.md
```

## Install dependencies

Run this in the project folder:

```bash
pip install -r requirements.txt
```

## Run the server

Start the app with Uvicorn:

```bash
uvicorn main:app --reload
```

The server will be available at:

- http://127.0.0.1:8000/
- http://127.0.0.1:8000/about

## Test the endpoints

### In a browser

Open these URLs in your browser:

- http://127.0.0.1:8000/
- http://127.0.0.1:8000/about

### With curl

```bash
curl http://127.0.0.1:8000/
curl http://127.0.0.1:8000/about
```
