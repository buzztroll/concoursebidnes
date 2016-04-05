FROM ubuntu:14.04

RUN apt-get update
RUN apt-get install -y unzip wget golang
RUN wget https://releases.hashicorp.com/packer/0.10.0/packer_0.10.0_linux_amd64.zip
RUN unzip packer_0.10.0_linux_amd64.zip
RUN mv packer /usr/bin
