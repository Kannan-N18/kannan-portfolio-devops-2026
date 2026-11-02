

\# Kannan's Portfolio - Docker Deployment



\## Project Description

Personal portfolio website containerized using Docker and Nginx.



\## Technologies

\- HTML

\- Docker

\- Nginx



\## Build Docker Image



docker build -t kannan-portfolio:v1 .



\## Run Container



docker run -d -p 8080:80 --name my-portfolio kannan-portfolio:v1



\## Access Application



http://localhost:8080



\## Stop Container



docker stop my-portfolio



\## Start Container



docker start my-portfolio



