## Docker run commands

### build docker image in current directory

docker build . 

### run a docker instance

docker run <imagename> 

run detached: 
docker run -d <imagename> 

### show current running container

docker ps

### stop container

docker stop <containername>

## Docker "debug" commands

### go into container instance

docker exec -it <containername> /bin/bash

### cp from container 

docker cp <containername>:/<src_in_container> <host_dest_path>

### cp into container

docker cp <host_src_path> <containername>:/<dest_in_container>

## Docker "compose" commands

### run a compose file
docker-compose up

