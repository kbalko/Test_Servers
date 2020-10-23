# Test_Servers
server/docker

Apache2 and Nginx in Docker container

commands:

$ docker build -t webserver . 
$ docker run -d -p 8080:80 --name www webserver 
$ docker exec -it webserver sh # run a command inside docker container (run shell)
