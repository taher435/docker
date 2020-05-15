# Download base node image
FROM node:10.16.3

SHELL ["/bin/bash", "-c"]

# update package list
RUN apt-get update

# Install Angular CLI
RUN npm install -g --unsafe-perm @angular/cli@8.3.17
