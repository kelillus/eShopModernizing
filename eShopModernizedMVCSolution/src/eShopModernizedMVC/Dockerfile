FROM microsoft/aspnet:4.7.1
ARG source
WORKDIR /inetpub/wwwroot
EXPOSE 80
#COPY ${source:-obj/Release/publish} .
RUN powershell -command Get-ChildItem .
COPY /obj .
RUN powershell -command Get-ChildItem .
#Copy D:/a \\?\C:\ProgramData\docker\tmp\docker-builder852680135\a: The system cannot find the file specified.
#COPY . . No error
# COPY \Obj . \\?\C:\ProgramData\docker\tmp\docker-builder267257027\Obj: The system cannot find the file specified.
