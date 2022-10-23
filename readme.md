# find docker version
 docker version
#Instructions
Star with an OS
Install Node
Copy app files
Run node app.js

#build docker
docker build -t docker-learning .
#show docker image list
docker image ls
or
docker images
#docker run
docker run hello-docker
#To push a new tag to this repository
docker push nazmuljuit/docker-learning:tagname
docker tag docker-learning nazmuljuit:latest

====chapter 2: Linux Command Line===
#ubuntu run in docker
docker run ubuntu
#View running container
docker ps

#View stop container
docker ps -a
#run ubuntu locally
docker run -it ubuntu
#find root user
whoami
#location of the shall program 
echo $0
#find all packages 
apt list

=====Chapter-3: Linux file system======
#create a new directory
mkdir
#create a new file 
touch
#move file
mv
#remove file or directory
rm
#install nano
apt install nano
#list of files
ls
#content of the files
cat file1.txt