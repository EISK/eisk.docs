---
uid: eisk-webapi-download-options-visx
---
# EISK Web Api - Visual Studio Extension (VSIX)

## Installion

You can install EISK as part of Visual Studio and create as many instances of projects as you want from Visual Studio -> File menu.

1) **Download:** Download the Visual Studio Extension from [Visual Studio Gallery](https://marketplace.visualstudio.com/items?itemName=AshrafulAlam.Eisk) or from [Github Release](https://github.com/EISK/eisk.webapi/releases). 

2) **Install:** Once downloaded simply click the VSIX file, which will install the extension in your Visual Studio instance.

## Create a New Project

1) **Open Visual Sudio and find the template:** After the installation is complete, open your visal studio and follow the steps below: From Visual Sutio menu, click *File -> New -> Project*. In the "Create a new project" window, go to the "Search for templates" textbox and type "eisk". You'll find "Eisk Web Api" in the search result. Simply click the item. 
2) **Select the template:** Once you click to select the template, "Configure your new project" window wil appear. 
3) **Creating a project:** Give a project name, which will also be used as the root namespace of your project (for instance: Eisk). Then click "Create". 

This is enable you to create a new solution with all EISK projects loaded in your Visual Studio instance.

## Running the Project

1) Locate the web api project from the solution (it will be named as `the project name you provided`.WebApi, example: Eisk.WebApi). 
2) Right click the project, and from the context menu, select "Set as Startup Project". 
3) Simply hit "Ctrl + F5" from your keyboard. You will see Visual Studio will load EISK Web API in your browser!

## Explore and Code!

Congrats! You've EISK loaded in your Visual Studio! Enjoy exploring the code and make changes as you want.

Check the [here](xref:eisk-webapi-handson-walkthrough-create-service-api) to get hands on on experience with EISK Web Api. 
