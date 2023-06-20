# Социальная сеть Kittygram
### URL
Проект развернут на сайте:
https://kittytask.hopto.org/
### Описание
Интерактивный сайт с личным кабинетом с возможностями публикации
фотографий котов, а также присваивания достижений.
### Технологии
Python 3.11.1,
Django 3.2.3,
Django REST framework 3.12.4,
Node.js 18
### Запуск проекта в dev-режиме
- Клонируйте репозиторий и перейдите в него в командной строке:
```
git clone https://github.com/georgii265/kittygram_final.git
```
```
cd kittygram_final
```
- Запустите проект с помощью команды:
```
docker compose up
```
- Соберите статику Django с помощью команды:
```
docker compose exec backend python manage.py collectstatic
```
- Скопируйте статику командой:
```
docker compose exec backend cp -r collected_static/. ../static/static/
```
- По адресу http://127.0.0.1:9090/ сайт будет доступен.

### Автор
Георгий Моргунов (https://t.me/gera265)