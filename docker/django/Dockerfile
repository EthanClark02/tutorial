# base is the latest Python container on DockerHub
FROM python:latest
# update pip, the Python package manager; may not be necessary but won't hurt
RUN pip3 install --upgrade pip
# install Django into the root Python; RUN runs INSIDE the container as root
RUN pip3 install django
# set working directory for when the image is spun up in a container
WORKDIR /src