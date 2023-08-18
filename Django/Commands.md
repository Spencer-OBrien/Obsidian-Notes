### Creating an app

```bash
django-admin startproject projectname
```
how to start a new project 

```bash
python3 manage.py startapp app_name
```
create a new app in Django 
- don't forget to add it to 'INSTALLED_APPS' in the settings.py file

- add templates folder to app_name and inside it make another app_name


```bash
python3 manage.py makemigrations app_name
```

```bash
python3 manage.py migrate
```

```bash
python3 manage.py shell
```
open the Django shell

```bash
python3 manage.py runserver
```
runs the server
```bash
python3 manage.py dbshell
```
open the database shell

```bash
from blog.models import Post
```
importing from our models 

```bash
a = Post(title="Newsletter", text="Hello World",author=user)
p.save()
print(p)
```
then instantiating an instance of the model 
in this case the author is a foreign key


```bash
python manage.py shell_plus
```
to open shell plus

```bash
Post.objects.all()
```
to queer the whole whole database

```bash
Post.objects.filter(title="Newsletter")
```
to get the news letter

```bash
Post.objects.filter(title__contains="e")
```
to get all posts that contain the letter e in the title