# Docker Flask App

A simple Flask app running inside a Docker container.

## Run it:
```bash
docker build -t flaskapp .
docker run -p 5000:5000 flaskapp
