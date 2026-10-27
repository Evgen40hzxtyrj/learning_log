# Learning Log

Web application for keeping a personal learning journal. Users can create topics, add entries to them and track their progress.

🔗 **Live demo:** https://evgen43.pythonanywhere.com

## Features
- User registration and authentication
- Create, edit and view topics and entries
- Each user sees only their own data
- Interface in Russian, Ukrainian and English (Django i18n)
- Responsive design with Bootstrap 4

## Tech stack
- Python 3.10, Django 5.2
- SQLite
- Bootstrap 4 (django-bootstrap4)
- Deployed on PythonAnywhere

## Run locally
```bash
git clone https://github.com/Evgen40hzxtyrj/learning_log.git
cd learning_log
python -m venv venv
venv\Scripts\activate        # Windows; on Linux/macOS: source venv/bin/activate
pip install -r requirements.txt
echo SECRET_KEY = 'any-dev-key' > learning_log/secret.py
python manage.py migrate
python manage.py runserver
```
