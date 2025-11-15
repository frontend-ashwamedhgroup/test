web: python manage.py collectstatic --noinput && gunicorn resume.wsgi:application --workers 5 --threads 2 --worker-class gthread --bind 0.0.0.0:$PORT
