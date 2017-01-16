docker-litmus
================

Dockerized Litmus WebDAV Test Server Suite

Build the Docker image:
```
docker build -t <tag it> .
```
The Litmus container can be started and you may modify or rerun the tests.
```
docker run -ti <ID of your Litmus container> litmus https://<IP of your cardDAV Server>/ <username> <password>
```
