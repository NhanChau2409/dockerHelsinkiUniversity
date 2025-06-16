# Docker Helsinki University Express App

A simple Express.js application for the Docker Helsinki University course.

## Running the application

### Using Docker

```bash
docker build -t docker-helsinki-university .
docker run -p 8080:8080 docker-helsinki-university
```

### Using Docker Compose

```bash
docker-compose up -d
```

Access the application at http://localhost:8080 