создан README.md
проверить установлен ли docker и docker compose
bash docker compose --version
создать docker-comopose.yml
bash touch docker-compose.yml

docker exec -it deepseek-ollama-open-webui-ollama-1 ollama pull deepseek-r1:1.5b
docker exec -it deepseek-ollama-open-webui-ollama-1 ollama list 