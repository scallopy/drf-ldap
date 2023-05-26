# drf-ldap

## Creaate a new Django project and init with git:

- In Github create an empty repository:

git@github.com:scallopy/drf-ldap.git

- In command line:

```
$ virtualenv -p /usr/local/bin/python3.8 env
$ source venv/bin/activate
$ django-admin startproject product_drf
$ cd product_drf/
$ echo "# product_drf" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin git@github.com:scallopy/drf-ldap.git
$ git push --set-upstream origin master
$ git add .
$ git commit -m "Create django project"
$ git push origin master

```
## Create superuser:

```
$ python3.8 manage.py migrate
$ python3.8 manage.py createsuperuser
```

## Start app product:

```
$ django-admin startapp product
```

## Create Product model:

```
$ python3.manage.py makemigrations
$ python3.8 manage.py migrate
```
