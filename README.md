# Cloning the repo from Git hub

- With SSH :
> git clone git@github.com:maroua-j/TP-DOCKER.git

- With HTTPS :
> git clone https://github.com/maroua-j/TP-DOCKER.git

# Docker compose MYSQL & Wordpress & Phpmyadmin

The docker-compose.yml file takes care of downloading the images used in the project.

To create a MYSQL container, a Wordpress container and a Phpmyadmin container with the docker-compose.yml :

> docker compose up -d

The MySQL server starts on port 3306
The Wordpress starts on port 8000 (localhost:8000)
The Phpmyadmin starts on port 8081 (localhost:8081)

# MySQL

- Database name : mydb

- Database user name : root123

- Database password : azerty

# Phpmyadmin

http://localhost:8081/

- User : root123

- Password : azerty

# Useful links

Git hub : https://github.com/maroua-j/TP-DOCKER

Docker hub images :

- Database mysql : 
> docker pull marouajf/db

- Phpmyadmin : 
> docker pull marouajf/pma

- Wordpress : 
> docker pull marouajf/wordpress

# Tools used 

- Visual Studio Code

- Docker

- GitHub

# Authors

- Nicolas GROS

- Maroua JAI FAYEZ