# Django Vue Template Project

Intended to be used as a template for future projects

## Setup

### Requirements
* [Node](https://nodejs.org) - try running `node --version` in terminal/cmd to see if you already have it
* [Python](https://python.org) - try running `python --version` in terminal/cmd to see if you already have it
* [Pipenv](https://pypi.org/project/pipenv/) - after installing python, install with `pip install --user pipenv`

### Setup Template

```
$ git clone https://github.com/matt-nathan/django-vue-template
$ cd django-vue-template
```

### Backend Setup
```
$ pipenv install --dev && pipenv shell
$ python manage.py migrate
```

### Frontend Setup
```
$ npm install
```

### Running Backend
```
$ python manage.py runserver
```

### Running Frontend
```
$ npm run serve
```

Now, you can access the frontend at http://localhost:8080 and the backend at http://localhost:8000
