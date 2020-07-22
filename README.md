1.share this node app  as zip or repo
2. unzip app or pull from repo
3.cd /app
4. build image from dockerfile
	docker build -t docker-101 .
5. run the container from image built
	docker run -dp 3000:3000 docker-101