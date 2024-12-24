### DJANGO FOLDER STRUCTURE BEST PRACTICE
```mermaid
django_backend_folder/
│
├── manage.py
├── Procfile
├── Dockerfile
├── .dockerignore
├── setup.cfg
├── setup.py
├── MANIFEST.in
├── README.md
├── LICENSE.md
├── Body.md
├── .gitignore
├── .pylintrc
├── .env
│
├── django_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── route.py
│   ├── urls_public.py
│   ├── auth.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── django_app/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── urls.py
│   ├── api/
│   │   ├── __init__.py
│   │   ├── api_1.py
│   │   ├── api_2.py
│   │   ├── api_3.py
│   ├── path/
│   └── migrations/
│
├── templates/
│   ├── base.html
│   ├── index.html
│   └── redoc.html
│
├── utils/
│   ├── helpers.py
│   ├── backup.py
│   ├── middleware.py
│   ├── enum.py
│   ├── exception.py
│
└── static/
    ├── css/
    ├── js/
    └── images/
```