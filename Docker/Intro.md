### What is docker ?
Docker is container platform that allows you to build , test , and deploy applications quickly.

### Why use Docker ?
Using Docker can help you ship your code faster , gives you control over your applications.

Docker-based applications can be seamlessly moved form local development machines to production deployments. You can use docker for Microservices, Data processing, Continuos Integration and Delivery, Containers as service.

![Docker](https://dev-to-uploads.s3.amazonaws.com/i/3puuhxmfe85kcfxn0jtm.png)

### How does it work ?
Containerization Vs Virtualization

An application on VM requires a guest OS and thus an underlying hypervisor to run.

In software world, containerization is an efficient method for deploying applications.

A container encapsulates an application with its own operating system.

### Docker Architecture 
Docker uses a client server architecture. The docker client talks to the Docker daemon , which does the heavy lifting of building, running, and distributing your docker containers.

**Docker deamon : it listens to the API requests being made through docker cli and manages Docker objects such as images, containers, network and volumes.**

*Docker clinet this what you use to interact with Docker.*

### Docker registries
This is where Docker images are stored with Docker.
Docker Hub

### Dockerfile
**Describes steps to create a Docker image. This images can be pulled to create containers in any environment.
when you run docker image you get docker containers.**

### Docker image
A docker image is a file that defines a Docker Container.
Docker image is run to create a docker container. Images are immutable.Once built, the files making up an image do not change.
Images can be stored locally or remote locations like hub,docker.com

### Container
A container is a runnable instance of an image.This where your application is running.
- is a runnable instance of an image. You can create, start, stop, move, or delete a container
using the DockerAPI or CLI.
- can be run on local machines, virtual machines or deployed to the cloud.
- is portable(can be run on any OS)
- Containers are isolated from each other and run their own software, binaries and configurations.

### Container Volumes
Each container starts from the image defination each time it starts.
While containers can create, update and delete files, those changes are lost when the container is removed and 
all changes are isolated to thata container.
**With volumes we can change this**
