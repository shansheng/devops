# Readme

    DevOps
    
# Usage

    docker run -d --name mysql primetoninc/mysql:5.6
    docker run -d -p 8080:8080 --name devops --link mysql:mysql primetoninc/devops:latest


    docker run -d -p 8080:8080 --name devops -e MYSQL_DATABASE=devops -e MYSQL_USER=devops -e MYSQL_PASSWORD=devops -e MYSQL_HOST=111.111.111.111 primetoninc/devops:latest

    