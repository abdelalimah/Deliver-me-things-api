## Dockerized mysql & phpMyAdmin for easy access

## Setup

<dl>
  <dt>install docker-compose</dt>

    https://docs.docker.com/compose/install/
       
  <dt>copy and past the following commands in your terminal :</dt>

    git clone git@github.com:abdelalimah/mysql-phpMyAdmin.git
    cd Deliver-me-things-api
    git checkout develop
    touch .env && echo "MYSQL_ROOT_PASSWORD=root" > .env
    docker-compose up -d

</dl>
