# escape=`
FROM microsoft/aspnet:4.7.1
ARG source
WORKDIR /inetpub/wwwroot
EXPOSE 80
#COPY ${source:-obj/Release/publish} .
COPY . .

#Copy D:/a \\?\C:\ProgramData\docker\tmp\docker-builder852680135\a: The system cannot find the file specified.
