# DOCKER

**Docker** is a self-contained environment that includes everything we need for local development: web services, databases, and more if we want. The general pattern will always be the same when using it with Django:

- create a new virtual environment and install Django 
- create a new Django project within it 
- write a Dockerfile and build the initial image 
- write a docker-compose.yml file and run the container with docker-compose up