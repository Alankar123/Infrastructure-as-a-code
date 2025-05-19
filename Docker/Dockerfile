# Using a base image
FROM alpine:latest

# Copying script into the image
COPY hello.sh /hello.sh

# Make it the default command when container runs
ENTRYPOINT ["/bin/sh","/hello.sh"]
