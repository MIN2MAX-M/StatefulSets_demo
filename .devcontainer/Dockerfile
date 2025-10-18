
FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install common DevOps tools
RUN apt-get update && \
    apt-get install -y \
      ca-certificates \
      curl \
      apt-transport-https \
      gnupg \
      lsb-release \
      jq && \
    curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash && \
    rm -rf /var/lib/apt/lists/*
