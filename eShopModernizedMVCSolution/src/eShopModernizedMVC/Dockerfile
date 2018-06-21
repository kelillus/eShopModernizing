# FROM microsoft/aspnet:4.7.1
FROM microsoft/aspnet
ARG source
WORKDIR /inetpub/wwwroot
EXPOSE 80
COPY ${source:-obj/Docker/publish} .
