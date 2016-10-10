web: gunicorn config.wsgi:application
worker: celery worker --app=newmsa.taskapp --loglevel=info
