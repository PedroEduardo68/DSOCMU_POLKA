# Base image
FROM ubuntu:20.04

ENV TZ=America/Sao_Paulo
ENV DEBIAN_FRONTEND=noninteractive

# Avoid interactive prompts during package installation
RUN ln -fs /usr/share/zoneinfo/$TZ /etc/localtime
RUN apt-get update
RUN apt-get install -y curl iputils-ping htop wget git vim ca-certificates  software-properties-common build-essential nano 
RUN apt-get install -y tzdata
RUN dpkg-reconfigure --frontend noninteractive tzdata

# Default command
CMD ["/bin/bash"]