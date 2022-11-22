# Simple MongoDB-Server-Docker-Compose
A simple MongoDB Server template based on Docker Compose

## Getting started
1. Clone and get into this repo
```bash
git clone https://github.com/geeksloth/mongodb-server-docker-compose.git && cd mongodb-server-docker-compose
```

2. Modify your desire ```password``` in the *docker-compose.yml* or *docker-compose-with-express.yml* to your desire password.

3. Run *Docker Compose* in detached mode
```bash
docker compose up -d
```
or
```bash
docker-compose -f docker-compose-with-express.yml down
```

