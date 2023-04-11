# Docker-commands

to remove all container that are running

docker container prune

You can remove stopped containers using the command

docker container prune 
or if you want to clean volumes, networks etc. too, you can do

docker system prune
If you rarely need to access a stopped container, you can make it a habit to add the --rm flag to your docker run commands. Then docker will remove the container when it stops.

If you just want to remove a single container, you can do

docker rm mymet2
