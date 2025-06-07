## Basic Docker Commands

Docker Image Commands

	docker pull <image-name>     -> download docker images
 
	docker images      -> list all downloaded images
 
	docker image ls
 
	docker rmi <image-id>	
 
	docker build
	

Docker Container Commands
	
	docker run <image-name>
 
		docker run -it <image-name> /bin/bash
  
		docker exec -it <cont-id> /bin/sh
	
	docker start <cont-id>
 
	docker stop <cont-id>
	
	dokcer ps       ->list all running container
	docker ps -a    ->list all running and non-running containers
