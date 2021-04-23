# esphome_docker-compose
ESPHome (https://esphome.io/) запущенный через docker-compose

### Адрес для доступа к консоли
*http://IP_ADDR_HOST:6052#*

### Команды
#### Пересоздать контейнер  
```
docker-compose up --build -d --remove-orphans --force-recreate
```
#### Удалить контейнер  
```
docker-compose down --remove-orphans
```
#### Обновить образ  
```
docker pull esphome/esphome
```

