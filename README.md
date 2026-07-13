# MLOPS-Docker-Masterclass

A simple Flask web app built for learning Docker basics.

## What it does

- Shows a form where you can enter your name
- Submits the form and greets you with a welcome message
- Built to demonstrate how to containerize a Python Flask app using Docker

## Tech Used

- Python
- Flask
- Docker

## How to Run Locally (without Docker)

1. Clone this repo

```bash
   git clone https://github.com/Sonalikasingh17/MLOPS-Docker-Masterclass.git
   cd MLOPS-Docker-Masterclass
```

2. Install Flask

```bash
   pip install flask
```

3. Run the app

```bash
   python app.py
```

4. Open your browser and go to `http://localhost:5000`

## How to Run with Docker

1. Build the Docker image

```bash
   docker build -t flask-docker-demo .
```

2. Run the container

```bash
   docker run -p 5000:5000 flask-docker-demo
```

3. Open your browser and go to `http://localhost:5000`

## Project Structure

```
├── app.py         # Main Flask application
├── Dockerfile      # Docker build instructions
└── README.md
```
## Purpose

This project was made as a learning exercise to understand how to package and run a simple Python web app inside a Docker container.
