FROM mcr.microsoft.com/devcontainers/base:bullseye

# Install basic build tools if needed
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends git curl ca-certificates
