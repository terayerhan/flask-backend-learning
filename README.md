# Flask Backend Learning

This repository follows the official Flask tutorial while I learn the fundamentals of backend web development with Python.

Tutorial source:  
https://flask.palletsprojects.com/en/stable/tutorial/

## Goals

The goal of this project is to understand how a Python web backend is structured and how HTTP requests flow through a web framework.

Topics covered include:

- Flask application structure
- Routing and request handling
- Jinja templates
- SQLite database integration
- Authentication
- Blueprints and modular application design

## Project Status

Work in progress while following the Flask tutorial.

## Running the Project

The following instructions assume a **Linux environment** (tested on Ubuntu/Kubuntu).

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install Flask
```

Run the development server:

```bash
flask --app flaskr run
```

Open in your browser:

```
http://127.0.0.1:5000
```

## Notes

This project is intended for learning and experimentation while studying backend development concepts such as HTTP, routing, and server-side application structure.