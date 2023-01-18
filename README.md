# Mysql 5.7 x PHPMyadmin

## This package include:
- Mysql 5.7 at port 3306
- PHPMyadmin at port 8088

## System requirements
- Docker CLI, Docker Compose CLI
- Linux OS
## Setup steps:
- Open docker-compose.yml to reconfigure data storage paths & share path between host & docker container
- Run ``docker-compose up -d`` at root
- Access: ``http://localhost:8088/`` for PHPMyadmin