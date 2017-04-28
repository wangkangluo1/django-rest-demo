web: gunicorn mysite.wsgi
worker: celery worker -A mysite.celery --loglevel=info --logfile=worker.log -B
