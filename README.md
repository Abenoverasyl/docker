# Docker
Necessary things for docker


### show docker images:
docker images



### Sow running containers:
docker ps


### Show all containers:
docker ps -a

### Set container name on run
docker run _--name_ hello _937_

### Delete container
docker rm 7791867076ee

### Output all containers id
docker ps -a -q

### Delete all containers
 docker rm $(docker ps -qa)
 
