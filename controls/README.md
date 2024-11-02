# Agenda-Project

Iniciar o projeto Django

```
python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
python manage.py startapp contact
python manage.py
python manage.py runserver
```

Configurar o git

```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT
```

Migrar a BD do Django - cada vez que fizer alterações nos models

```
python manage.py makemigrations
python manage.py migrate
```

Criar e modificar a password de um Super User Django

```
python manage.py createsuperuser
python mangage.py changepassword USERNAME
```