# Set the base image to use for subsequent instructions
FROM alpine:3.23

# Set the working directory inside the container
WORKDIR /usr/src

# Copy any source file(s) required for the action
COPY entrypoint.sh .

# Create a non-root user and switch to it
RUN  chmod +x /usr/src/entrypoint.sh

# Configure the container to be run as an executable
ENTRYPOINT ["/usr/src/entrypoint.sh"]
