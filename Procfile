web: pybabel compile -d src/translations && gunicorn src.app:app
init: python src/manage.py db init
migrate: python src/manage.py db migrate
upgrade: python src/manage.py db upgrade
