# Agility.AspNetCore
dotnet core SDK for Agility CMS Sync Model targeting `NetCore 3.1`.

The package can be installing from NuGet
```
PM> Install-Package Agility.AspNetCore
```
Learn how to setup the Agility.AspNetCore package in your dotnet core application [here](https://help.agilitycms.com/hc/en-us/articles/360019026211-Agility-AspNetCore).


## How to build:
From the downloaded source code, `cd AgilityWebCore` and run the following command to build a Release version of the Agility.AspNetCore.dll

`> dotnet publish -o ../builds`

## How to pack a Nuget Package
 From the downloaded source code, `cd AgilityWebCore` and run the following command

`> dotnet pack -o ../nupkgs`

## How to publish as a Nuget Package
From the `AgilityWebCore` and run command the following command

`> dotnet nuget push ../nupkgs/Agility.AspNetCore --source https://api.nuget.org/v3/index.json --api-key xxxxxxxxxxxxxxxxxxxxxxxxxxx`


Follow the [ASP.NET Core](https://help.agilitycms.com/hc/en-us/sections/360002696372-ASP-NET-Core) section on our help site for latest help/guide articles.
