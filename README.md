# pi-hole
1. Install docker
   1. [Manage Docker as a non-root user](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user)
1. Install docker-compose
   1. automatic selection of binary does not work properly. Use link with explicit architecture: ```sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-linux-armv6" -o /usr/local/bin/docker-compose``` for raspberry pi 1 for example.
1. checkout this repository in ```/opt/```
1. add password
1. run ```docker-compose up --detach```

docker-compose from [here](https://hub.docker.com/r/pihole/pihole)
