# Cloning the repo from Git hub

- With SSH :
> git clone git@github.com:maroua-j/TP-DOCKER.git

- With HTTPS :
> git clone https://github.com/maroua-j/TP-DOCKER.git

# Docker compose MYSQL & Wordpress & Phpmyadmin

To create a MYSQL container, a Wordpress container and a Phpmyadmin container with the docker-compose.yml :

> docker compose up -d

The MySQL server starts on port 3306
The Wordpress starts on port 8000 (localhost:8000)
The Phpmyadmin starts on port 8081 (localhost:8081)

The docker-compose.yml file takes care of downloading the images used in the project.

# Useful links

Git hub : https://github.com/maroua-j/TP-DOCKER
Docker hub : https://hub.docker.com/