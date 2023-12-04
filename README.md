# Flexi_Booking
new project


will follow this structure 

TomcatDockerWar/
├── .git/
├── Dockerfile
├── README.md
├── src/
│   └── main/
│       └── webapp/
│           └── index.jsp
├── venv/  # (Virtual environment - assuming it's created during development)
├── your_app_name/
│   ├── templates/
│   │   └── seat_booking/
│   │       └── index.jsp  # (Symlink or copy from src/main/webapp/index.jsp)
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   └── urls.py
├── manage.py
└── your_project_name/
    ├── __init__.py
    ├── asgi.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py

