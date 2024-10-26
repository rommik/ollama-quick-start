# Use the base image specified in devcontainer.json
FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

# Set the working directory
WORKDIR /workspace

# Install any additional dependencies
# RUN apt-get update && apt-get install -y <package-name>

# Install Python dependencies if you have a requirements.txt
# COPY requirements.txt .
# RUN pip install --user -r requirements.txt

# Set the default command to keep the container running
CMD ["tail", "-f", "/dev/null"]
