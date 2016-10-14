# Docker Symfony

A simple Docker container for Symfony projects.

To start a new project in your current directory:
```
docker run -it --rm -v $(pwd):/app tebro/symfony symfony new <your_app_name>
```


To run commands in your project (example: run the dev server):
```
docker run -it --rm -v $(pwd):/app tebro/symfony php bin/console server:run
```
