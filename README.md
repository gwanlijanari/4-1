запустить в терминале (по порядку)
docker compose -f compose.yaml --profile monitoring up -d
docker compose -f compose.yaml run --rm ansible banner.yml

сайт
http://localhost:8080

прометей
http://localhost:9090

графана
http://localhost:3000

