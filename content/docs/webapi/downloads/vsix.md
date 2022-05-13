---
uid: eisk-webapi-download-options-visx
---
# EISK Web Api - Visual Studio Extension (VSIX)

You can install EISK as part of Visual Studio and create as many instances of projects as you want from Visual Studio -> File menu.

## Step by Step Guide

1) **Download:** Download the Visual Studio Extension from [Visual Studio Gallery](https://marketplace.visualstudio.com/items?itemName=AshrafulAlam.Eisk) or from [Github Release](https://github.com/EISK/eisk.webapi/releases). 

2) **Install:** Once downloaded simply click the VSIX file, which will install the extension in your Visual Studio instance.

3) **Open Visual Sudio and Find the Template:** After the installation is complete, open your visal studio and follow the steps below: From Visual Sutio menu, click *File -> New -> Project*. In the "Create a new project" window, go to the "Search for templates" textbox and type "eisk". You'll find "Eisk Web Api" in the search result. Simply click the item.

4) **Create New Project from Template:** Once you click to select the template, "Configure your new project" window wil appearch. Give a project name, which will also be used as the root namespace of your project (for instance: Eisk). Then click "Create".

5) **Open and Run the Created Project:** Locate the web api project from the solution (it will be named as <the project name you provided>.WebApi, example: Eisk.WebApi). Right click the project, and from the context menu, select "Set as Startup Project". Simply hit "Ctrl + F5" from your keyboard. You will see Visual Studio will load EISK Web API in your browser!

Congrats! You've EISK loaded in your Visual Studio! Enjoy exploring the code and make changes as you want.