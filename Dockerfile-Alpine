# Use a specific version of the official Alpine image as base
FROM alpine:3.14

# Set environment variable
ENV MY_VERSION=3.14

# Install necessary packages or copy files
RUN apk add --no-cache bash

# Example of using the environment variable
RUN echo "The Alpine version is $MY_VERSION"

# Command to run the container
CMD ["echo", "Hello from Alpine $MY_VERSION"]
