# docker-compose_with-django
https://docs.docker.com/compose/django/#connect-the-database


Connect the database

In this section, you set up the database connection for Django.

    In your project directory, edit the composeexample/settings.py file.

    Replace the DATABASES = ... with the following:

    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.postgresql',
            'NAME': 'postgres',
            'USER': 'postgres',
            'HOST': 'db',
            'PORT': 5432,
        }
    }

