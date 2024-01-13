# Docker App for Get SH>IT Done!

Get SH>IT Done Carrousel - Docker App (2024)


## Download the code and Build the container
> git clone https://github.com/Juli-BCN/get-shit-done-docker.git

> cd get-shit-done-docker

> docker build -t get-sh-it-done .

> docker images


## Upload to Docker Hub
```bash
docker image tag get-sh-it-done julibcn/get-sh-it-done
docker login -u julibcn
docker image push julibcn/get-sh-it-done
```