1. Connect to docker host and run command in step 2 on host 
2 git clone "https://github.com/nancybnsl/DockerDemo"
3. cd DockerDemo/
4. build image from dockerfile
	docker build -t docker-101 .
5. run command - docker images to verify image created with name docker-101	
6. run the container from image built
	docker run -dp 3000:3000 docker-101
7. to verify container is up and running , run command - docker ps
8. to verify port 3000 is open , run command netstat tulpn | grep LISTEN
