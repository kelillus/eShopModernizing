FROM microsoft/aspnet:4.7.1
ARG source
WORKDIR /inetpub/wwwroot
EXPOSE 80
RUN powershell -command Get-ChildItem .
COPY ${source:-obj/Docker/publish} .
#COPY /obj .
RUN powershell -command Get-ChildItem .
#Copy D:/a \\?\C:\ProgramData\docker\tmp\docker-builder852680135\a: The system cannot find the file specified.
#COPY . . No error
# COPY \Obj . \\?\C:\ProgramData\docker\tmp\docker-builder267257027\Obj: The system cannot find the file specified.
