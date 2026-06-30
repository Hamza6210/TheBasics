# Day 3 - Docker Basics

## What I learned
- Image vs container (recipe vs running instance)
- Container vs virtual machine
- docker run, docker ps, docker ps -a, docker images
- docker stop and docker rm
- Port mapping with -p (host:container)
- docker exec -it to get inside a running container
- Ran Nginx and accessed it via port mapping
- Ran Postgres and connected with psql
- Volumes: data is lost without -v, survives with it
- Debugged a real Postgres 18 volume path error using docker logs
- Built a custom image with a Dockerfile (FROM, WORKDIR, COPY, CMD)
- docker build -t to create an image from a Dockerfile
- Docker Compose: defining multi-container setups in docker-compose.yml
- docker compose up -d and docker compose down
