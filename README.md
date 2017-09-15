# docker-tutorial-devops
Learn Docker and Devops from Udemy course. Docker Technologies for DevOps and Developers

Docker Technologies for DevOps and Developers  
https://www.udemy.com/docker-tutorial-for-devops-run-docker-containers

1. Docker
2. DevOps
3. Docker Compose
4. Docker Swarm
5. Docker Machine
6. DockerHub
7. CirclCI
8. DigitalOcean

Show docker images list
```
  > docker images
```
Login DockerHub
```
  > docker login
```
docker run
```
  > docker run busybox:1.24 echo "hello world"
  > docker run busybox:1.24 ls /
  > docker run -it busybox:1.24 (interactive mode)
  > docker run -d busybox:1.24 sleep 1000 (docker run in background mode)
  > docker run --rm busybox:1.24 sleep 1 (remove when finish run)
  > docker run --name hello_world busybox:1.24 (define name for container)
```
docker inspect
```
  > docker inspect <container id>
```
docker inspect
```
  > docker inspect <container id>
```

docker logs
```
  > docker run -it -d -p 8888:8080 tomcat:8.0
  > docker logs <container id>
```