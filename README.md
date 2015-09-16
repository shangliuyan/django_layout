##Introduction
django_layout is one style to organize django code.
now it base 1.8.4, layout looks like below:

├── README.md
├── conf
├── docs
├── requirements.txt
└── src
    ├── manage.py
    ├── project_name
    │   ├── __init__.py
    │   ├── settings
    │   │   ├── __init__.py
    │   │   ├── base.py
    │   │   ├── dev.py
    │   │   └── prod.py
    │   ├── urls.py
    │   └── wsgi.py
    ├── static
    │   ├── css
    │   ├── image
    │   └── js
    ├── templates
    └── utils
        └── __init__.py



##usage
```sh
django-admin.py startproject --template=https://github.com/shangliuyan/django_layout/zipball/master  project_name
```
