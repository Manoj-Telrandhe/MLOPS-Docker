# MLOps-Docker

Learning Docker for MLOps by building and experimenting with containerized workflows.

---

## Docker

Docker is a software platform that packages software into containers.

Docker is a containerization platform that you can use to package software in containers and run them on target machines. Docker containers run on any machine or virtual machine where the Docker Engine is installed.

---

## Difference between Docker Image and Docker Container

### Docker Image

Docker images are read-only templates that contain instructions for creating a container.

A Docker image is a snapshot or blueprint of the libraries and dependencies required inside a container for an application to run.

A Docker image (or container image) is a standalone, executable file used to create a container. It contains all the libraries, dependencies, and files that the container needs to run. Docker images are shareable and portable, allowing the same image to be deployed across multiple environments—similar to a software binary file.

---

### Docker Container

A Docker container is a runtime environment with all the necessary components—such as code, dependencies, and libraries—needed to run the application code without relying on host machine dependencies.

---

### Creating Docker Containers from Docker Images

To create a container from a specific Docker image, you can use the basic `docker run` command.

This command creates a container from an image file and starts it.

---

### Key Differences: Docker Images vs Docker Containers

A Docker container is a self-contained, runnable software application or service.  
A Docker image, on the other hand, is the template or set of instructions used to create and run a container.

---

### Mutability

Docker images are **immutable**, meaning they cannot be modified once created.  
If changes are required, a new image must be built with the desired modifications.

In contrast, Docker containers are **mutable** and allow changes during runtime.  
Any changes made inside a container are isolated to that container and do not affect the original image.
