# Dockerized Two-Tier App

This repository is an extension of the [two-tier-flask-app](https://github.com/LondheShubham153/two-tier-flask-app) repository. It demonstrates how to containerize a two-tier application using Docker and optimize the image size.

## Repository Contents

This repo contains two Dockerfiles:

1. **Dockerfile** – A standard Dockerfile that creates an image of **564MB**.
2. **Dockerfile-multistage** – A multi-stage build that optimizes the image size to **223MB**.

Using a multi-stage Docker build helps reduce the final image size, making it more efficient for production deployment.

## Image Scanning with Docker Scout

To ensure security and best practices, **Docker Scout** is used to scan the images.

## Additional Resources

For a complete step-by-step guide, check out this blog post:  
🔗 [Complete Guide for Docker for Beginners](https://medium.com/@abhiraj2001/complete-guide-for-docker-for-beginners-97e2308dfafe)
