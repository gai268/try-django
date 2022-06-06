# try-django
## Application Launch
```
cd mysite
python manage.py runserver
```
## Migrate
```
python manage.py migrate
```

## Create an Admin User
```
python manage.py createsuperuser
```
Now, open a web browser and go to "/admin/" on your local domain -- e.g., http://127.0.0.1:8000/admin/. You should see the admin's login screen:

## Tests
```
python manage.py test polls
```