FROM mcr.microsoft.com/devcontainers/typescript-node:1-20-bullseye
RUN apt update && apt install -y zip unzip && \
  curl "https://awscli.amazonaws.com/awscli-exe-linux-aarch64.zip" -o "awscliv2.zip" && \
  unzip awscliv2.zip && rm -rf awscliv2.zip && ./aws/install && \
  npm install -g aws-cdk 