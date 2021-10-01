# sitkmutt-static-web

## How to run with Docker

```bash
# Build Docker Image for rating service
docker build -t seogram:dev .

# Run web-static service on port 3000
docker run -d --name web-static -p 3000:80 seogram:dev
```

## How to run with Docker Compose

```bash
docker-compose up -d --build
```