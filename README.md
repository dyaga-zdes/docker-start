# docker-start
_Запускаем битрикс на докере с трафиком

# TODO-LIST
- traefik:
  - сделать доступ к dashboard по https
- adminer:
  - сделать доступ по https


# Установка
1) добавить записи в файл hosts, где \$PROJECT_NAME заменить на значение константы из файла .env
> \$PROJECT_NAME.local  
> traefik.\$PROJECT_NAME.local  
> adminer.\$PROJECT_NAME.local
2) запустить контейнеры командой ```docker compose up -d```
3) ...