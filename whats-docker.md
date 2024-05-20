# What's Docker?

## Why Docker?
Docker is used to solve the following problem:
- Environment Consistency and Dependency Management: applications often behave differently in different environments (development, testing, production) 
due to variations in the underlying OS, installed libraries, and configurations.
- Portability across Platforms: moving application between different environments, such as from a developer's laptop to a production server,
can be error-prone and time-consuming due to differences in OS, hardware, and configurations.
- Isolation & Resource Allocation: running multiple applications on the same host can lead to conflicts (e.g. port conflicts, dependency clashes)
and inefficient resource utilization.
- Efficient Use of Resources: Virtual Machines provide isolation but are resource-intensive, as each VM runs a full OS and requires significant overhead.
- Simplifying CI/CD: integrating code changes, testing, and deploying applications can be complex and error-prone, especially under multiple environments
and dependencies.

## What's Docker?
Docker is an open-source platform that automates the deployment, scaling, and management of applications through 
containerization. Here's a detailed explanation of what Docker is and its key components:
- Containers: a container is a lightweight, **standalone**, and **executable** package of software that includes everything needed
to run an application - code, runtime, system tools, libraries, and settings. Containers are completely isolated from each
other.
- Docker Engine
- Docker Images: a Docker image is a lightweight, **standalone**, **immutable** file that contains the source code, libraries, 
dependencies, tools, and other files needed to run an application.
- Docker Hub
- Dockerfile: a Dockerfile is a text file containing a series of commands and instructions that are used to create a Docker
image.