# escape=`
FROM microsoft/aspnet:4.7.1
ARG source
WORKDIR /inetpub/wwwroot
EXPOSE 80
#COPY ${source:-obj/Release/publish} .
RUN powershell -command Get-ChildItem Env:
RUN powershell -command Get-Location
RUN powershell -command Get-ChildItem .
RUN powershell -command Get-ChildItem \



COPY \ .

#Copy D:/a \\?\C:\ProgramData\docker\tmp\docker-builder852680135\a: The system cannot find the file specified.
#COPY . . No error
COPY \Obj . \\?\C:\ProgramData\docker\tmp\docker-builder267257027\Obj: The system cannot find the file specified.
