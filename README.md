# weekl

libs:
    python -m pip install Django==2.2.7
    pip install django-cms
    pip install djangocms-text-ckeditor
    pip install django-filer
    pip install djangocms_bootstrap4
    pip install djangocms-link djangocms-file djangocms-picture djangocms-video djangocms-googlemap djangocms-snippet djangocms-style djangocms-column
    
    https://django-cms.readthedocs.io/en/latest/introduction/01-install.html - pip install djangocms-installer
GIT:   
    rm -rf /var/weekl/
    mkdir /var/weekl
    cd /var/weekl
    git clone -b master https://cheprasovstas:NQR4Cw6JwrVcJuM@github.com/cheprasovstas/weekl.git
    
    
django commands start:
                cd /var/weekl/weekl/weekl
                source /root/djangoenv/bin/activate;
                python manage.py runserver 0.0.0.0:80 &
                    env:
                        export SERVER_NAME=weekl-app.com;
                        export SERVER_PORT=80;
                        export DATABASE_HOST=check-in.vps-cheprasov.host4g.ru;
                        export DATABASE_PORT=5432;
                        export DATABASE_USER=checkin;
                        export DATABASE_PASSWORD='!QW@1qw2';