# docker
this is a docker
sudo -i
apt update
apt install docker.io
docker --version
docker images (all images)
docker rmi sonarqube -f(delete images)
docker rmi sonatype/nexus3 -f
docker images
docker ps (container run)
docker rm  sonar2  -f
docker ps -a
docker rm sonar
docker rm nexus
docker ps
docker run --name 5pm batch -d -p 5000:9000 sonarqube:latest
docker login
username :devopsvmr
password:jjqjkdqui
docker pull sonarqube:latest(image create)
docker images
sonarqube running
docker run --name myc1 -d -p 5000:9000 sonarqube:latest
(public ip copy :5000)
docker stop myc1(refresh chesthe work avadhu)
docker start myc1(refresh chesthe work avudhudhi)
docker ps
docker run --name 5 pm batch -d -p 89:80 nginx:latest
docker ps
running
(public ip copy :89)
docker images 
docker ps (to list all containers running)
docker stop myc1
docker ps -a
docker ps -a-q (only container ids)
docker start myc1
docker ps
docker inspect myc1  container id/ name (all details container id /name)
docker exec -it  myc1 /bin/bash (to navigate inside  the container lopalaki velatham)
ls
exit
docker exec -it 5 pm batch /bin/bash
ls
exit
cd /usr
cd share
ls
cd nginx
cd html
ls
cat >index.html
this is docker
ctrl c
refresh this is docker
exit
docker logs myc1
docker system df (to disk usages)
docker stop myc1
docker system df
docke stats --no-stream (to display live stream of containers resources usages statics)
docker rm  5pm batch -f
docker ps
docker rm  $ (docker ps -a -q ) -f (to  delete all running containers at a time)
docker ps -a






sudo -i
apt update
apt install docker.io
docker pull sonarqube:latest
docker run --name myc1 -d -p 5000:9000 sonarqube:latest
docker ps
docker ps -a
docker ps -a -q
docker exec -it myc1 /bin/bash
docker ps
docker stats --no-stream 
docker images
docker docker system df
docker stop
docker start
docker rm myc1 -f
docker rm $ (docker ps -a -q) -f
docker login
docker logs
cd /usr
cd share
cat > index.html

docker search nexus



docker full nginx:latest
docker images
docker pull prashanth92929/kubernetes:latest
docker images
docker pull skhilar/kubernetes sample:latest
docker images
docker pull tomcat:latest
docker images
docker images -q
docker history nginx
docker rmi tomcat:latest
docker images
docker rmi -f  $ (docker images) (to remove all docker images in our local  system at time)
docker images
docker file
FROM (the from directive is used to set  base image for the subsequent instructions, A docker file  must have FROM  directive with valid  image name as the first instruction.)
LABEL
RUN
COPY(the copy  directive used for  copying  files and directories host system to the during build, this instruction can be used only  for locally stored files.)
ADD()
CMD
ENTRYPOINT
WORKDIR
EXPOSE(the expose directive indicates  the ports on which a container will listen  for the connections, expose 80,expose 443)
ENV $ARG
vim docker file

FROM nginx:latest
LABEL maintainer "madhu"
RUN   apt update -y $$ apt install git -y
COPY ./index.html/usr/share/nginx/html
EXPOSE 80
save
vi index.html
hello all ! wellcome  to docker
save
cat dockerfile
cat index.html
docker build  -t  (imagename )5 pm batch .
docker images
docker run -- name  myc1 -d -p 89:80 5 pm batch :latest
docker exec -it  myc1 /bin/bash
cd usr
cd share
cd index.html
FROM nginx:latest
LABEL maintainer "srikanth"
RUN apt update -y $$ apt install git -y
CMD ls -l
docker build  -t  5pm batch 1.
docker images
docker run  -it 5pm batch1


docker file
FROM tomcat:latest
LABEL maintainer "madhu"
RUN   apt update -y $$ apt install git -y
CMD ls -l 

vi docker file

FROM tomcat:latest
LABEL maintainer "madhu"
RUN   apt update -y $$ apt install git -y
ENTRY POINT ["echo " ,  "welcome  to v cube"]

FROM tomcat:latest
LABEL maintainer "madhu"
RUN   apt update -y $$ apt install git -y
WORKDIR /usr/share

jrnkins  manage plugins install
docker and docker pipeline and docker build setup



docker volume

docker volume  create v cube
docker volume  ls
docker inspect vcube
docker volume create vcube1
docker volume ls
docker volume create vcube2
docker volume ls
mkdir myvolumes $$ cd myvolumes
ls
mkdir / home /backup
docker run -v /home/backup:/vcube-run --name  myc1 -d -p 84:80 nginx:latest

docker run -v /home/backup:/vcube-run --name  myc4 -d -p 80:80 nginx:latest
docker run -v /home/backup:/vcube-run --name  myc5 -d -p 84:80 tomcat:latest
docker exec -it  myc4 /bin/bash
ls
df -h
cd v cube
ls 
cat > f1
this is  1st file  in myc5 container
exit
ls
cd /home/backup
ls
docker volume rm  vcube
docker volume ls

















