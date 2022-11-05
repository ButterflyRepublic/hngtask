# hngtask

Your stage 2 task is centred around containerisation :package:.

 You are provided a simple application with the frontend in JavaScript(React) and backend in Python(Django). Follow instructions on how to deploy the application locally on your server. It should look like this. NB: It should have your slack display name
 You are then required to build docker images of the frontend and backend using a Dockerfile for each and push them to a docker repository eg docker hub, ecr etc.
 You are then required to create a docker-compose file that can spin up images into containers and are connected with one another. A simple docker-compose up should be able to start the application. If successful the frontend application should run on port 3000 of your server IP.
 You are then required to use reverse proxy with NGINX to point port 3000 to the IP of your server.
