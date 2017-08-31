# Readme

    DevOps
    
# Usage

    docker run -d --name mysql primetoninc/mysql:5.6
    docker run -d -p 8080:8080 --name devops --link mysql:mysql primetoninc/devops:latest
