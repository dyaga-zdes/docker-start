# docker-start
Запускаем битрикс на докере с трафиком

TODO-LIST
- traefik:
  - сделать доступ к dashboard по https

Установка
1) добавить в hosts $PROJECT_NAME.local и traefik.$PROJECT_NAME.local (где $PROJECT_NAME заменить на значение консстанты из файла .env)
2) запустить контейнеры docker compose up -d
3) ...