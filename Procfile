web: gunicorn api.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
main.py migrate
