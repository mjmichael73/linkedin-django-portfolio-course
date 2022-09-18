# recipe-app-api
This is the dockerized project for LinkedIn Django Portfolio Course.

Commands:

        docker-compose run --rm app sh -c "django-admin startproject app ."
        docker-compose run --rm app sh -c "flake8"
        docker-compose run --rm app sh -c "python manage.py test"