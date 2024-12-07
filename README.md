### Сборка контейнера и запуск
```bash
docker build . -t tnginx:v1
docker run --rm --name tnginx -d -p 80:80 tnginx:v1
```
### Проверка
```bash
curl localhost:80
```

### Остановка
```bash
docker stop tnginx
```
