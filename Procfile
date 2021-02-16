web: gunicorn superlists.wsgi :lists --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate