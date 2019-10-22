# microservices
## useful commands
### To see docker images
```
sudo docker images
```
### To see docker containers
```
sudo docker ps -a
```
### To create docker image
```
sudo docker build -t */imageName/* .
```
### To delete docker image
```
sudo docker rmi */imageName1 or image id1/* */imageName2 or image id2/* */imageName3 or image id3/* 
```
### To stop running docker
```
Press Ctrl + C
```
### To start docker-compose file
```
sudo docker-compose up
```

### To stop conatiner  runnig with docker-compose file
```
sudo docker-compose kill
```
### To remove all the stopped containers
```
sudo docker container prune
```
### To remove container forcefully while running
```
sudo docker rm -f */container name or container Id/*
```
### To check mongodatabase status
```
sudo service mongod status
```
### To start or stop mongodatabase 
```
sudo service mongod start
sudo service mongod stop
```
### To check engagged Port 
```
netstat -lnp
```
### To check netstat , first you need  to install net-tools
```
sudo apt install net-tools
```
### To kill a process in a port
```
sudo fuser -k */PortNo/*/*/Network type like tcp or udp/*
example : sudo fuser -k 8092/tcp
```

#### Created By Arkoprobho Pal

