# Docker Symfony

A simple Docker container for Symfony projects.

To start a new project in your current directory:
```
docker run -it --rm -u $(id -u) -v $(pwd):/app tebro/symfony symfony new <your_app_name>
```


To run commands in your project (example: run the dev server):
```
docker run -it --rm -u $(id -u) -v $(pwd):/app -p 8000:8000 tebro/symfony php bin/console server:run 0.0.0.0:8000
```
