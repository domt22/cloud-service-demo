# Cloud Service Demo

## Purpose: To learn the git and github, and their commonly used features (creating, checking status, stage, commit, push, and branches).

## Files Included: README.md, index.html & Dockerfile.
Version Control helps a cloud project because it allows for simple and smooth process for collaborating and easy recovery by commits and pushes of files.

### What is Docker?
Docker is a platform which runs applications within isolated environments (containers).
### What is a Docker Image?
A Docker Image is a snapshot of a directory or code.
### What is a Docker Container?
A Docker Container is running version of the image that is built and run.
### How to build and run the application using Docker:
 * Build: "docker build -t cloud-service-demo:1.0 ."
 * Run: "docker run -d --name cloud-demo-container -p 8080:80 cloud-service-demo:1.0"
 
