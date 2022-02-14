# Dockerized Angular Development Environment

This container keeps the Angular hot reload functionality while it runs from Windows 10 host.

### Host Environment

- Nodejs: v16.14.0
- NPM: 8.3.1

### Useful commands

#### NPM

- ```npm install``` 
    - to keep modules references into your IDE

#### 
- ```docker-compose up --build ``` 
    - to runs the application inside a docker container

- ```docker-compose down```
    - to stop and remove containers, images and volumes

- ```docker exec -ti angular-app /bin/sh```
    - to access the container's bash
