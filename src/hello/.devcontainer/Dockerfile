FROM mcr.microsoft.com/devcontainers/base:${templateOption:imageVariant}

RUN echo "no color" > /usr/local/etc/greeting.txt \
    && chown -R vscode:vscode /usr/local/etc/greeting.txt \
    && cd /usr/local/etc \
    && ls -la \