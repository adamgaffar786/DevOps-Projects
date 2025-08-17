# Flask Docker App

A simple Python Flask application containerized with Docker.

## How to Run

1. Build the Docker image:
   ```bash
   docker build -t flask-docker-app .
   ```

2. Run the container:
   ```bash
   docker run -p 5000:5000 flask-docker-app
   ```

3. Open in your browser: [http://localhost:5000](http://localhost:5000)

## Tools Used
- Python
- Flask
- Docker
