FROM mcr.microsoft.com/devcontainers/base:${templateOption:imageVariant}

RUN echo "no color" > /usr/local/etc/greeting.txt \
    && cd /usr/local/etc \
    && ls -la
#     # && chown -R vscode:vscode /usr/local/etc/devcontainers/greeting.txt