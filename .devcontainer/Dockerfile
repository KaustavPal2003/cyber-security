FROM mcr.microsoft.com/vscode/devcontainers/python:3.8

USER root

# Install necessary packages
RUN apt-get update && apt-get install -y python3-pip tcpdump libpcap-dev
RUN pip3 install scapy

USER vscode
