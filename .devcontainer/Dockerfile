FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu-20.04

# Install MySQL client
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends mysql-client
