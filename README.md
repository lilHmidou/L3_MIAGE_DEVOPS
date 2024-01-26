First install docker desktop for your distro : 

https://www.docker.com/products/docker-desktop/

Command to build the stack
$ docker compose build

Command to rebuild the stack without cache
$ docker compose build --no-cache

Command to launch the stack
$ docker compose up -d

Command to stop the stack
$ docker compose down

Command to launch a process whithin a container, it stands for interactive, lets you interact with the process in your terminal
$ docker exec -it <your container name> <the process to start>
Example for this project 
$ docker exec -it miage-php sh