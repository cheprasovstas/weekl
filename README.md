# weekl

libs:
    python -m pip install Django==2.2.7
    pip install django-cms
    pip install djangocms-text-ckeditor
    pip install django-filer
    pip install djangocms_bootstrap4
    pip install djangocms-link djangocms-file djangocms-picture djangocms-video djangocms-googlemap djangocms-snippet
    djangocms-style djangocms-column
    
    https://django-cms.readthedocs.io/en/latest/introduction/01-install.html - pip install djangocms-installer

django commands start:
                cd /var/weekl/weekl/
                source /var/weekl/venv/bin/activate
                python manage.py runserver 0.0.0.0:80 &
                    env:
                        SERVER_NAME=localhost
                        SERVER_PORT=8000
                        DATABASE_HOST=check-in.vps-cheprasov.host4g.ru
                        DATABASE_PORT=5432
                        DATABASE_USER=checkin
                        DATABASE_PASSWORD=!QW@1qw2