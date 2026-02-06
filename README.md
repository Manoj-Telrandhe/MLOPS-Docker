# MLOPS-Docker
Learning Docker for MLOps by building and experimenting with containerized workflows.


##Docker:
Docker is a software platform that packages software into containers. 
Docker is a containerization platform that you can use to package software in containers and run them on target machines. Docker containers run on any machine or virtual machine where the Docker engine is installed

##Difference b/w Docker Image Vs Docker Container :
###Docker Image:
Docker images are read-only templates that contain instructions for creating a container. 
A Docker image is a snapshot or blueprint of the libraries and dependencies required inside a container for an application to run.

A Docker image, or container image, is a standalone, executable file used to create a container. This container image contains all the libraries, dependencies, and files that the container needs to run. A Docker image is shareable and portable, so you can deploy the same image in multiple locations at once—much like a software binary file. 


###Docker containers:
A Docker container is a runtime environment with all the necessary components—like code, dependencies, and libraries—needed to run the application code without using host machine dependencies.

###Creating Docker containers from Docker images:
To create a container from a specific Docker image, then use the basic Docker run command.
The command creates a container from an image file.


###Key differences: Docker images vs. Docker containers
A Docker container is a self-contained, runnable software application or service. On the other hand, a Docker image is the template loaded onto the container to run it, like a set of instructions.

###Mutability:
Docker images are immutable, which means they can’t be modified once created. If changes need to be made to an image, you must create a new image with the desired modifications.

In contrast, containers are mutable and allow modifications during runtime. Changes made within a container are isolated to that particular container and don’t affect its associated image.

