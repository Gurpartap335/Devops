### Docker overview
Docker is an open platform for developing, shipping, and running applications.
Docker enables you to separate your applications from your infrastructure so can 
deliver software quickly.

### The Docker platform
Docker provides the ability to package and run an application in a loosely environment
called **container.** The isolation and security allows you to run many containers 
simultaneously on a given host.

### What can i use Docker for?
Containers are great for continous integration and continuous delivery(CI/CD) workflows.

Docker containers can run on 
- developer laptop 
- physical or virtual machines in a data center
- cloud providers
- mixture of environment

#### Running more workloads on the same hardware
Docker is lightweight and fast.
its provide alternative to hypervisor based virtual machines, so can use more of your computer capacity to achieve your business gaols.

### Docker architecture
Docker uses a client-server architecture.

The Docker *client* talks to the docker daemon which does the heavy lifting of building,
running, and distributing your docker containers.

**THE docker client and daemon communicate using a REST API over unix sockets or a network interface**

Docker daemon (dockerd)

### Images
An image is a read-only template with instruction for creating a Docker container.

DockerFile -> image -> contaiener.

### Containers
A container is a runnable instance of an image.
You can create, start, stop, move, or delete a container using the Docker API or CLI.
You can connect to one or more networks, attach storage to it or even create a new image
based on its current state

**A container is defined by its image as well as any configuration options you provide to it when you create or start it.when a container is removed, any changes to its state that are not stored in persistent storage disappear.**

### underlying technology
Docker is written in the Go programming language and takes advantage of several features of linux kernel to deliver its functionality. Docker uses a technology called namespaces to provide the isolated workspace called the container.