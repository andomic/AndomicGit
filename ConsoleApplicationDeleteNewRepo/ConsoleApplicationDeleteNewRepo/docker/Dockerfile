FROM mcr.microsoft.com/windows/servercore
ADD . /app
WORKDIR /app
ENTRYPOINT ["cmd.exe", "/k", "OWIN.Docker.exe"]