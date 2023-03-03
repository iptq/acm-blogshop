FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Download Zola and put it in /usr/local/bin
RUN apt-get update && apt-get install -y wget git
RUN wget -q -O - \
"https://github.com/getzola/zola/releases/download/v0.16.1/zola-v0.16.1-x86_64-unknown-linux-gnu.tar.gz" \
| tar xzf - -C /usr/local/bin