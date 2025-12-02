# Base image
FROM ubuntu:22.04

ENV TZ=America/Sao_Paulo
ENV DEBIAN_FRONTEND=noninteractive

# Avoid interactive prompts during package installation
RUN ln -fs /usr/share/zoneinfo/$TZ /etc/localtime
RUN apt-get update
RUN apt-get install -y curl iputils-ping nano htop mtr telnet htop linux-headers-generic sudo wget  git vim ca-certificates  software-properties-common build-essential nano mtr fping tcpdump dnsutils nmap telnet ssh whois net-tools tar
RUN apt-get install -y tzdata
RUN dpkg-reconfigure --frontend noninteractive tzdata

#RUN apt-get install flex bison dwarves libssl-dev libelf-dev bc

WORKDIR /sdep4

#Copy project files (uncomment if needed)
COPY . .

# Default command
CMD ["/bin/bash"]