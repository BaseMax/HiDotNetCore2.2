# Dot Net Core 2.2

Max@Base:~$ dotnet --version
---------
```
2.2.301
```

$ dotnet
-------------
```
Usage: dotnet [options]
Usage: dotnet [path-to-application]

Options:
  -h|--help         Display help.
  --info            Display .NET Core information.
  --list-sdks       Display the installed SDKs.
  --list-runtimes   Display the installed runtimes.

path-to-application:
  The path to an application .dll file to execute.
```

Max@Base:~/ttt$ dotnet new mvc --auth Individual
-----------------
```
The template "ASP.NET Core Web App (Model-View-Controller)" was created successfully.
This template contains technologies from parties other than Microsoft, see https://aka.ms/aspnetcore-template-3pn-210 for details.

Processing post-creation actions...
Running 'dotnet restore' on /home/max/ttt/ttt.csproj...
```


max@Base:~/ttt$ dotnet run
-----------------------
```
info: Microsoft.AspNetCore.DataProtection.KeyManagement.XmlKeyManager[0]
      User profile is available. Using '/home/max/.aspnet/DataProtection-Keys' as key repository; keys will not be encrypted at rest.
info: Microsoft.AspNetCore.DataProtection.KeyManagement.XmlKeyManager[58]
      Creating key {6ef1edd4-27eb-4978-8366-ab38d5c8d66b} with creation date 2019-07-10 19:16:01Z, activation date 2019-07-10 19:16:01Z, and expiration date 2019-10-08 19:16:01Z.
warn: Microsoft.AspNetCore.DataProtection.KeyManagement.XmlKeyManager[35]
      No XML encryptor configured. Key {6ef1edd4-27eb-4978-8366-ab38d5c8d66b} may be persisted to storage in unencrypted form.
info: Microsoft.AspNetCore.DataProtection.Repositories.FileSystemXmlRepository[39]
      Writing data to file '/home/max/.aspnet/DataProtection-Keys/key-6ef1edd4-27eb-4978-8366-ab38d5c8d66b.xml'.
Hosting environment: Development
Content root path: /home/max/ttt
Now listening on: https://localhost:5001
Now listening on: http://localhost:5000
Application started. Press Ctrl+C to shut down.
```
