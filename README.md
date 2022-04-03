

### Для запуска приложения:

```
docker-compose build urllist-app
```

Для запуска в режиме postgresql указать переменную окружения MEM_MODE:

```
docker-compose run -e MEM_MODE=POSTGRES -p 8000:8000 urllist-app
```

По-умолчанию запуск в режиме in-memory:

```
docker-compose run -p 8000:8000 urllist-app
```
