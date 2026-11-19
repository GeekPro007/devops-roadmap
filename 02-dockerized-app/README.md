# NexaTech Website – Docker Lab
## Project overview
This project packages the NexaTech preview website into a Docker image and runs it in a container using Nginx.
## Tools used
- Docker
- Dockerfile
- Docker Compose
- Nginx
## Run the project
Build and start the website:
```bash
sudo docker compose up -d --build
```
Open this address in your browser:
`http://localhost:8080`
## Useful commands
```bash
sudo docker compose ps
sudo docker compose logs
sudo docker compose stop
sudo docker compose start
sudo docker compose down
```
## What I learned
- What a Docker image and container are
- How a Dockerfile builds an image
- How port mapping makes the website available on my laptop
- How Docker Compose manages the container
## Note
The website has both frontend and backend in this Docker lab.
