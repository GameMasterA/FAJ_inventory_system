web: sh -c "python manage.py migrate && gunicorn inventory_system.wsgi:application --bind 0.0.0.0:$PORT"
