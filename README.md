# recipe-app-api
Recipe app api source code



##### Create core app
```
docker-compose run app sh -c "python manage.py startapp core"
```
Delete some files, create tests folder and __init__.py file

##### Create custom user model




##### Test

```
docker-compose run app sh -c "python manage.py test && flake8"
```