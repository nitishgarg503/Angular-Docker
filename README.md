# Angular-Docker

Commands

To start Docker image - sudo docker run -p 4300:80 frontend:v2   [80 is nginx or webserver port,container port and 4300 is browser port, host port]

To build Docker image - sudo docker build -t frontend:v2 .

To start Docker image with container name - sudo docker run -p 4300:4300 --name angular-container -d frontend:v2

List Docker images - sudo docker images  

List Docker containers - sudo docker ps -a

Delete Docker image with container name - sudo docker rmi -f angular-container-2 4b92d5d14ad5 

Delete Docker image -  sudo docker rmi -f 4b92d5d14ad5
