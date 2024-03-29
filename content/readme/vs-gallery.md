EISK makes it easy to write scalable and secured web api on top of Microsoft's new cutting edge .net based technologies. 

With an optional set of customizable utility classes, samples and tools, it lets you creating new web api straight away without wide technical experience or learning curve.

## Give a Star! :star:

If you like or are using this project to learn or start your solution, please give it a [star](https://github.com/EISK/eisk.webapi). Thanks!

## Core Technologies

* Platform: [.NET Framework 6.0](https://devblogs.microsoft.com/dotnet/announcing-net-6/) - The Fastest .NET Yet!
* Web Framework: ASP.NET Web API 
* ORM Framework: Entity Framework
* Programming Language: C#

## Sample Use Case

Using a simple data entity 'Employee', EISK shows how we can build scalable web api's easily along with addressing real-world domain and business use cases, including: 

* [C]reating a new employee record
* [R]ead existing employee records
* [U]pdate an existing employee record
* [D]elete an existing employee record

![eisk web api](https://raw.githubusercontent.com/EISK/eisk/master/eisk-webapi-small.png)

Check the [Live Demo](https://eisk-webapi.azurewebsites.net) to see the use case implementation in action.

## Dev Features

You can build your own RESTful web api using EISK's Visual Studio and ASP.NET Web API project template. 

The template includes (but not limited to), project structure and all utility classes mentioned below to enable building modern cloud-aware RESTful APIs.

* **Clean Architecture** based implementation
* **Swagger/OpenAPI** based RESTful Web API specification
* **Base classes** for common CRUD functionalities and testing for logical layers (i.e. controller, domain, data layers)
* **Utility classes** to generate real-world test data
* Support for database integration tests with both in-memory database and SQL server

## QuickStart Guide

1) **Download:** Download the Visual Studio Extension from [Visual Studio Gallery](https://marketplace.visualstudio.com/items?itemName=AshrafulAlam.Eisk) or from [Github Release](https://github.com/EISK/eisk.webapi/releases). 

2) **Install:** Once downloaded simply click the VSIX file, which will install the extension in your Visual Studio instance.

3) **Open Visual Sudio and Find the Template:** After the installation is complete, open your visal studio and follow the steps below: From Visual Sutio menu, click *File -> New -> Project*. In the "Create a new project" window, go to the "Search for templates" textbox and type "eisk". You'll find "Eisk Web Api" in the search result. Simply click the item.

4) **Create New Project from Template:** Once you click to select the template, "Configure your new project" window wil appearch. Give a project name, which will also be used as the root namespace of your project (for instance: Eisk). Then click "Create".

5) **Open and Run the Created Project:** After your project is created and loaded in Visual Studio as solution, locate the web api project from the solution (it will be named as <the project name you provided>.WebApi, example: Eisk.WebApi). Right click the project, and from the context menu, select "Set as Startup Project". Simply hit "Ctrl + F5" from your keyboard. You will see Visual Studio will load EISK Web API in your browser!

That's it!

## What's Next?

After running the created project successfully, you'll get an understanding about how the sample use case has been used to explore cutting edge technologies for building a web api.

Next - you can try some hands-on experience by creating your own api on top of your custom entity and see how quickly you can roll out an enterprise quality web api with similar quality and productivity. 

Utilities and code samples as provided in EISK have intentionally been designed to be self explaining. You may still want to get deeper understanding by exploring the documentations:

* [Live Demo](https://eisk-webapi.azurewebsites.net)
* [Hands-on Walk-through](https://eisk.github.io/docs/webapi/application-development/handson-walkthrough-create-service-api.html)
* [Logical Layer Architecture](https://eisk.github.io/docs/webapi/architecture/logical-layers.html)
* [Technology Stack](https://eisk.github.io/docs/webapi/technical-reference/technology-stack.html)

## Questions?

Should you have any questions or need any help to implement new cool features, you can [ask](https://stackoverflow.com/questions/ask?tags=eisk,webapi,asp.net-core&title=In%20EISK,%20How%20Do%20We%20..) in StackOverflow community with tag [eisk](https://stackoverflow.com/questions/tagged/eisk) and get prompt response.

[![NuGet Badge](https://buildstats.info/nuget/Eisk.WebApi)](https://www.nuget.org/packages/Eisk.WebApi/)   [![Build status](https://dev.azure.com/EiskOps/Eisk/_apis/build/status/Eisk-WebApi-TemplatePack-CI)](https://dev.azure.com/EiskOps/Eisk/_build/latest?definitionId=3)

