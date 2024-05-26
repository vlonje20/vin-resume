Thanks for downloading this template!

Template Name: iPortfolio
Template URL: https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/
Author: BootstrapMade.com
License: https://bootstrapmade.com/license/

Section Links:
[objects](#Docker Objects:)

Portfolio:
- app:
  - porfolio-1 a
  - porfolio-3 b
  - porfolio-6 c
- card:tools
  - porfolio-4 d
  - porfolio-7 e
  - porfolio-8 f
- web:
  - porfolio-2 g
  - porfolio-5 h
  - porfolio-9 i

```
copy me
```

##    copy me 

##
    copy me 

Headers:
# This is a sample 
## This is a sample
### This is a sample
#### This is a sample
##### This is a sample
###### This is a sample

<h1> This is a sample</h1>

+ this is a sample 
- this is a sample 
* this is a sample 

1. This is a sample 
2. This is a sample 

Docker Overview:
================
Containerization is a technology that allows applications and their 
dependencies to be packaged and run in a consistent environment, known as 
a container, across different computing environments. This eliminates the 
"It works on my machine" problem and ensures that the application runs the 
same way regardless of where it is deployed.

- Docker is an an open-source platform for developing, shipping, and running applications. 
- Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. 
- With Docker, you can manage your infrastructure in the same ways you manage your applications. 
- By taking advantage of Docker''s methodologies for shipping, testing, and       deploying code, you can significantly reduce the delay between writing code and running it in production.

 - Docker is a platform for running applications in an isolated environment called a "container" (or Docker container). 
 - A Docker container is in effect a "running instance" of a Docker image. 
 - From this perspective, an image is stored permanently more or less (i.e. insofar as image updates are published), whereas containers are stored temporarily.
 - Its cross platform; meaning it can run on all OS - Linux, Windows, Mac etc. 

Docker Platform:
- Docker provides the ability to package and run an application in a loosely isolated environment called a container. 
- The isolation and security lets you run many containers simultaneously on a given host. 
- Containers are lightweight and contain everything needed to run the application.
- You can share containers while you work, and be sure that everyone you share with gets the same container that works in the same way.


## Benefits of containerization:
- Portability: Containers can be easily moved between different environments 
  such as development, testing, and production without any changes.

- Efficiency: Containers share the host operating system''s kernel, making 
  them lightweight and efficient in terms of resource consumption.

- Scalability: Containers can be easily scaled up or down to meet 
  changing demands without a significant impact on performance.

- Consistency: Containers provide a standardized environment for 
  running applications, ensuring consistency across different environments.


Docker Architecture and Components:
===================================
- Docker build 
- Docker pull 
- Docker run 
- Docker push 

- Docker uses a client-server architecture. 
- The Docker client talks to the Docker daemon, which does the heavy lifting of building, running, and distributing your Docker containers. 
- The Docker client and daemon can run on the same system, or you can connect a Docker client to a remote Docker daemon. 
- The Docker client and daemon communicate using a REST API, over UNIX sockets or a network interface. 
- Another Docker client is Docker Compose, that lets you work with applications consisting of a set of containers.

- The Docker Daemon (dockerd):
  - Also known as docker engine, docker host 
  - Listens for Docker API requests and manages Docker objects such as images, containers, networks, and volumes. 
  - A daemon can also communicate with other daemons to manage Docker services.

-  Docker Client:
  - This is the primary way that many Docker users interact with Docker. 
  - When you use commands such as docker run, the client sends these commands to dockerd, which carries them out. 
  - The docker command uses the Docker API. 
  - The Docker client can communicate with more than one daemon.

- Docker Registry:
  - A Docker registry stores Docker images. 
  - Docker Hub is a public registry that anyone can use, and Docker looks for images on Docker Hub by default. 
  - You can even run your own private registry.
  - Docker Private Registry = ECR, Nexus, JFrog, DTR. 
  - When you use the docker pull or docker run commands, Docker pulls the required images from your configured registry. 
  - When you use the docker push command, Docker pushes your image to your configured registry.    


## Docker Objects:
- When you use Docker, you are creating and using images, containers, networks, volumes, plugins, and other objects. 
- This section is a brief overview of some of those objects.

Docker Images: 
  - This contains an application and all its dependencies packaged together. 
  - It is a read-only template with instructions for creating a Docker container.
  - Often, an image is based on another image, with some additional customization.For example, you may build an image which is based on the ubuntu image, but installs the Apache web server and your application, as well as the configuration details needed to make your application run.
  - You might create your own images or you might only use those created by others and published in a registry.
  - To create your own image, you need to use a Dockerfile  

Docker Containers: 
  - A container is a run time instance of an image. 
  - You can create, start, stop, move, or delete a container using the Docker API or CLI. 
  - You can connect a container to one or more networks, attach storage to it, or even create a new image based on its current state.
  - By default, a container is relatively well isolated from other containers and its host machine. 
  - You can control how isolated a container''s network, storage, or other        underlying subsystems are from other containers or from the host machine.


## Differences Between VM and Containers:
Resource Utilization: 
- VMs run a full operating system with its own kernel, which leads to higher resource consumption compared to containers. 
- Containers share the host''s operating system kernel and only run the application and its dependencies, making them more lightweight and efficient in terms of resource utilization.
