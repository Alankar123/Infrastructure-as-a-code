Docker Custom Image Build
This directory contains a basic example of building a custom Docker image using Alpine Linux as the base.

It demonstrates the following:
Creating a Dockerfile
Copying and executing shell scripts within a container
Managing container lifecycle using Docker CLI commandsagement.

# Build a custom image
docker build -t my-custom-image .

# Run the container 
docker run my-custom-image

# Verify your container 
docker ps -a
