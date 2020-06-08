# Django Celery


## Running Locally

```bash
python manage.py migrate
```

```bash
python manage.py runserver
```

```bash
celery -A mysite worker -l info
```

Make sure you have RabbitMQ service running.

```bash
rabbitmq-server
```

For more info see the Blog post.