# Docker

## delete all images 
`docker rmi $(docker images -a -q)`

## delete all containers 
`docker rm $(docker ps -aq)`

## delete all volumes
`docker volume prune`

## delete all containers
`docker container prune`
