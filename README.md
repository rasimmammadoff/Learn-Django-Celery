# Learn-Django-Celery
Periodic and shared tasks example in Celery with Redis 

![Alt text](example.jpg?raw=true "Title")

## Installation
```bash
pip install -r requirements.txt
```

## Redis
##### First Install Redis Server
## Start Redis Server
```bash
redis-server
```

## Starting the worker process
```bash
celery -A src worker -B -l info
```

## Run Django project
```bash
python manage.py runserver
```
