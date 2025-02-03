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

создан README.md
проверить установлен ли docker и docker compose
bash docker compose --version
создать docker-comopose.yml (hier beschreibe kurz wie die docker-compose.yml gemacht wurde)
bash touch docker-compose.yml
bash docker compose up -d
bash docker exec -it "container name" ollama pull deepseek-r1:1.5b
bash docker exec -it "container name" ollama list (prüfen ob das modell gepulled wurde)

im browser localhost:8080 aufrufen und chatten