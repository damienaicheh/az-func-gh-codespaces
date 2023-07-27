FROM mcr.microsoft.com/devcontainers/base:ubuntu-22.04

RUN curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

RUN sudo apt-get update && \
    sudo apt-get install -y dotnet-sdk-7.0 aspnetcore-runtime-7.0 dotnet-runtime-7.0

RUN curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg && \
    sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg && \
    sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/microsoft-ubuntu-$(lsb_release -cs)-prod $(lsb_release -cs) main" > /etc/apt/sources.list.d/dotnetdev.list'

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
     && apt-get -y install --no-install-recommends azure-functions-core-tools-4
