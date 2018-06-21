FROM microsoft/aspnet:4.7.1
ARG source
WORKDIR /inetpub/wwwroot
EXPOSE 80
RUN powershell -command Get-ChildItem .
COPY ${source:-obj/Docker/publish} .
RUN powershell -command Get-ChildItem .
