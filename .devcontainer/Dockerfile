FROM mcr.microsoft.com/azure-functions/dotnet-isolated:4-dotnet-isolated7.0
# FROM mcr.microsoft.com/devcontainers/base:ubuntu-22.04

# # [Optional] Uncomment this section to install additional OS packages.
# # RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
# #     && apt-get -y install --no-install-recommends <your-package-list-here>

# # [Optional] Uncomment if you want to install an additional version of node using nvm
# # ARG EXTRA_NODE_VERSION=10
# # RUN su node -c "source /usr/local/share/nvm/nvm.sh && nvm install ${EXTRA_NODE_VERSION}"

# # [Optional] Uncomment if you want to install more global node modules
# RUN curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

# RUN curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
# RUN sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg
# RUN sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/microsoft-ubuntu-$(lsb_release -cs)-prod $(lsb_release -cs) main" > /etc/apt/sources.list.d/dotnetdev.list'
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#      && apt-get -y install --no-install-recommends azure-functions-core-tools-4
# # RUN apt-get update  && export DEBIAN_FRONTEND=noninteractive && apt-get install -y apt-transport-https
# # RUN apt-get install azure-functions-core-tools-4

# RUN sudo apt-get update && \
#     sudo apt-get install -y dotnet-sdk-7.0 && \
#     sudo apt-get install -y aspnetcore-runtime-7.0 && \
#     sudo apt-get install -y dotnet-runtime-7.0