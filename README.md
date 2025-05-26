# docker-start
_Запускаем битрикс на докере с трафиком

# TODO-LIST
- traefik:
  - сделать доступ к dashboard по https
- adminer:
  - сделать доступ по https


# Установка
1) добавить записи в файл hosts, где bitrix-test заменить на значение константы \$PROJECT_NAME из файла .env
> bitrix-test.local  
> traefik.bitrix-test.local  
> adminer.bitrix-test.local
2) запустить контейнеры командой ```docker compose up -d```
3) ...