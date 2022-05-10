- What is Docker ?
Docker is a container platform that allows you to build , test and deploy applications
quickly . 
A developer defines all the applications and its dependencies in a Dockerfile which is 
then used to build Docker images that defines a Docker image that defines a Docker container .

Doing this ensures that your applications will run in any environment .


- why use Docker ?
Using Docker can help you ship your code faster , gives you control over 
your applications .
you can use docker for microservices , data percessing , continuous integration and delivery ,
containers as service .

- How does it work ?
Virtual machines 
app 1
bins/lab
guest os
hypervisor
infrastruture

containers
app 1
bins/lab
containers engine
operating system
infrastructure

In software world , constainerization is an efficient method for deploying 
applications .

- Docker Archittecture 
Docker uses a client-server Archittecture .
The docker clients talks to the docker daemon , which does the heavy lifting
of building , running and distributing your docker containers.

Docker daemon :
It listens to the API requests being made through the docker client and manages
Docker objects such as images , containers , networks and volumes .

- Docker clients

- Docker registries 
this is were Docekr images are stored .
Docker Hub is a public registry that anyone can use .
DOCKER_HOST image saved .

- Docker Runtime :

- Docker Engine : 

docker run hello-world  

