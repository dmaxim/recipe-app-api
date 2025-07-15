# recipe-app-api
Demo project for Udemy course

## Reference
Project based on REST API with Python course on Udemy.
https://www.udemy.com/course/django-python-advanced/


## Setup Environment

````
uv init
uv venv --python 3.9
source .venv/bin/activate

uv add -r requirements.txt

````

## Linting with flake8

````
docker compose run --rm app sh -c "flake8"
````