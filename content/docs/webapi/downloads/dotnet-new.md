---
uid: eisk-webapi-download-options-dotnet-new
---
# EISK Web Api - dotnet Cli

[dotnet cli](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-new) is comes with latest Visual Studio and  provides excellent command line options to create, build, test, deploy .net core application easily.

[![NuGet Badge](https://buildstats.info/nuget/Eisk.WebApi)](https://www.nuget.org/packages/Eisk.WebApi/)

## Installion

Installing this template in your local machine will allow you creating as many web api projects with EISK as you want. 

### Installing from Nuget Gallery

Consider the following simple walk through to install EISK in your local machine with dotnet cli. 

To install EISK Web Api template with dotnet cli, open command prompt, and type the following command:

`dotnet new -i eisk.webapi`

## Create a New Project

From the command prompt, navigate to a directory, where you want to create new web api and type the following command:

`dotnet new eiskwebapi -n Eisk`

The 'n' parameter accepts the root namespace of the project (in the given example this is Eisk). You can consider your company name or choice of your root namespace.

After the solution is created simply click the created solution to open in Visual Studio.

## Running the Project

1) Locate the web api project from the solution (it will be named as `the project name you provided`.WebApi, example: Eisk.WebApi). 
2) Right click the project, and from the context menu, select "Set as Startup Project". 
3) Simply hit "Ctrl + F5" from your keyboard. You will see Visual Studio will load EISK Web API in your browser!

## Explore and Code!

Congrats! You've EISK loaded in your Visual Studio! Enjoy exploring the code and make changes as you want.

Check the [here](xref:eisk-webapi-handson-walkthrough-create-service-api) to get hands on on experience with EISK Web Api. 
