# README:
## Для запуска выполнить: 
### docker-compose up -d --build
## После запуска выполнить следующие команды: 
### docker-compose exec django-app python manage.py migrate --noinput
### docker-compose exec django-app python manage.py collectstatic --no-input --clear