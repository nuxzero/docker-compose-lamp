# Docker Compose for LAMP stack

The template for using LAMP stack with Docker Compose.


## Installation

- Pull image `docker-compose pull`.
- Install `docker-compose build` and `docker-compose up -d`.
- Start all container `docker-compose start`.
- Stop all container `docker-compose stop`.
- Destroy all container `docker-compose down`.
- Shell to container `docker exec -it mysql sh` and `mysql -u user -p password`.


## Environments

- apache
- phpfpm
- mysql


## Database connection

- `DATABASE_NAME=database`
- `DATABASE_HOST=dockerdb`
- `USER=root`
- `PASSWORD=root`
