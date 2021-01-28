ARG SERVERCORE_VERSION
FROM mcr.microsoft.com/windows/nanoserver:${SERVERCORE_VERSION}
COPY configmap-reload.exe /configmap-reload.exe
ENTRYPOINT ["/configmap-reload.exe"]