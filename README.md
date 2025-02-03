# Deepseek Ollama + Open WebUI Setup

## Prerequisites
- Docker & Docker Compose installed  
```bash
docker compose --version
```
## Setup
- Create docker-compose.yml
```bash
touch docker-compose.yml
```
## Start the Container
```bash
docker compose up -d
```
## Pull the Model into the Container
```bash
docker exec -it "container name" ollama pull deepseek-r1:1.5b
```
## Verify the Model
```bash
docker exec -it "container name" ollama list
```
## Access the Application
```bash
http://localhost:8080
```