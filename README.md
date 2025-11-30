Start:
docker-compose -f docker-compose.dev.yml up -d

Rebuild:
docker-compose -f docker-compose.dev.yml up -d --build

Stop:
docker compose -f docker-compose.dev.yml stop

Remove:
docker-compose -f docker-compose.dev.yml down