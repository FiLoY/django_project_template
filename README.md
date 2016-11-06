

# django_project_template
This is my Django project template, which greatly simplifies the development

# Structure:

{{ project_name }}/  
├── src  
│   ├── templates  
│   ├── static  
│   ├── media  
│   ├── manage.py  
│   ├── core  
│   │   ├── wsgi.py  
│   │   ├── urls.py  
│   │   ├── settings  
│   │   │   ├── local.py  
│   │   │   ├── base.py  
│   │   │   └── __init__.py  
│   │   └── __init__.py  
│   ├── apps  
│   │   └── __init__.py  
│   └── __init__.py  
├── requirements.txt  
└── README.md  

# Installation manual:
```bash
django-admin startproject --template=https://github.com/FiLoY/django_project_template/archive/develop.zip project_name
```
