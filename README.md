## Docker-composeでDjango with SQlite

ref: [https://docs.docker.com/samples/django/](https://docs.docker.com/samples/django/)

### 1. Clone this repository.

`$ git clone https://github.com/atsushi0424/dj`

### 2. Create Django Project (Only the first time) .

`$ docker-compose run web django-admin startproject config .`

### 3. Start Django Project.

`$ docker-compose up`

and you'll see the Django welcome page at http://localhost:8188 on your favorite web browser.

### 4. Stop Django Project.

`$ docker-compose down`
