# Project_docker_service

Record my learning journey

create a service

docker service create alpine ping 8.8.8.8, can check using docker service ls

it will also create a container, docker container ls

if I want to duplicate it, docker service update "service ID" --replicas 2

if I bring down one container, docker will create the service again.

