ARG SERVERCORE_VERSION

FROM mcr.microsoft.com/powershell:nanoserver-${SERVERCORE_VERSION}

COPY configmap-reload.exe /configmap-reload.exe
USER ContainerAdministrator

ENTRYPOINT ["/configmap-reload.exe"]