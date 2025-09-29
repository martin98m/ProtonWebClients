FROM node:22.20-bullseye

# Create a non-root user (for VS Code Remote Containers)
RUN useradd -ms /bin/bash vscode \
  && mkdir -p /workspaces \
  && chown -R vscode:vscode /workspaces

USER vscode
WORKDIR /workspaces
