## Dockerized mysql & phpMyAdmin for easy access

## Setup

  ## install docker-compose

    https://docs.docker.com/compose/install/
       
  ## copy and past the following commands in your terminal :

    git clone git@github.com:abdelalimah/mysql-phpMyAdmin.git
    cd mysql-phpMyAdmin
    touch .env && echo "MYSQL_ROOT_PASSWORD=root" > .env
    docker-compose up -d


