# dockertutorial
Sample code in support of the presentation by the AST on docker.  This overview demonstrates what Docker is and why it is important.  We look at various docker commands such as the following:
<br/><br/>
docker network <br/>
docker-machine<br/>
docker images<br/>
docker container<br/>
docker-compose<br/>
docker inspect<br/>
<br/><br/>
We create images, start containers, pull images, create and build images from Dockerfiles and look at Docker compose
<br/><br/>
<b>Exercise</b>
<br/><br/>
The following URL https://serversforhackers.com/dockerized-app/docker-compose describes a three tier docker composed web application with a database.  
<br>
Use this as guidance to update the docker-compose.yaml file to 
<br>
The docker image for Mongodb is at https://hub.docker.com/_/mongo/ and can be pulled to your local environment with the command "docker pull mongo".  It will also get pulled without this command if it is listed in your docker-compose.yaml.
<br>
All of the offical software can be listed at:<br>
https://hub.docker.com/explore/
<br><br>
Some guidance of Mongodb in Docker is listed at https://docs.docker.com/samples/library/mongo/#start-a-mongo-instance.  The reference for MongoDB is at https://www.mongodb.com/.


