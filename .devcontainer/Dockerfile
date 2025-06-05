# .devcontainer/Dockerfile
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:20

# We’ll install PNPM globally, but you can skip this if you only use npm
RUN npm install -g pnpm

# (Optional) If you ever need to install apt-packages (e.g. ffmpeg, git, etc.), do:
# RUN apt-get update && apt-get install -y --no-install-recommends \
#    git \
#    libnss3 \
#    # … any other Linux tools you need

# Switch to “node” user (provided by the base image)
USER node

# The default WORKDIR in this image is /workspace, which matches our devcontainer.json.
