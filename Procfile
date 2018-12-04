web: gunicorn config.wsgi:application
worker: celery worker --app=AutotestCloud.taskapp --loglevel=info
