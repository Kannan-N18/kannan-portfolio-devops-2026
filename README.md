

# Kannan's Portfolio - Docker Deployment



## Project Description

Personal portfolio website containerized using Docker and Nginx.



## Technologies

- HTML

- Docker

- Nginx



## Build Docker Image



docker build -t kannan-portfolio:v1 .



## Run Container



docker run -d -p 8080:80 --name my-portfolio kannan-portfolio:v1



## Access Application



http://localhost:8080



## Stop Container



docker stop my-portfolio



## Start Container



docker start my-portfolio

## Docker Deployment



The portfolio is containerized using Docker and served using Nginx Alpine.



### Docker Images

- kannan-portfolio:v1

- kannan-portfolio:v2

- kannan-portfolio:v3



### Running Containers

- Portfolio v1: http://localhost:8080

- Portfolio v3: http://localhost:8081



### Verification

Both portfolio versions returned HTTP 200 OK.



### Technologies

- Docker

- Nginx Alpine

- HTML

- Git

- GitHub

