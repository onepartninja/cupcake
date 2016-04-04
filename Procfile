web: gunicorn config.wsgi:application
worker: celery worker --app=cupcake.taskapp --loglevel=info
