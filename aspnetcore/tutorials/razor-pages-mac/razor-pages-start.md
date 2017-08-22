---
title: Getting started with Razor Pages in ASP.NET Core on Mac
author: rick-anderson
description: Getting started with Razor Pages in ASP.NET Core using Visual Studio for Mac
keywords: ASP.NET Core,Razor Pages,scaffolding,Entity Framework Core,EF,EF Core,database,mac,macOS,Visual Studio for Mac
ms.author: riande
manager: wpickett
ms.date: 7/27/2017
ms.topic: get-started-article
ms.technology: aspnet
ms.prod: aspnet-core
uid: tutorials/razor-pages-mac/razor-pages-start
---
# Getting started with Razor Pages in ASP.NET Core with Visual Studio for Mac

By [Rick Anderson](https://twitter.com/RickAndMSFT)

This tutorial will teach you the basics of building an ASP.NET Core Razor Pages web app. We recommend you complete [Introduction to Razor Pages](xref:mvc/razor-pages/index) before starting this tutorial. Razor Pages is the recommended way to build UI for web applications in ASP.NET Core.

## Prerequisites

Install the following:

* [.NET Core 2.0.0 SDK](https://dot.net/core) or later.
* [Visual Studio for Mac](https://www.visualstudio.com/vs/visual-studio-mac/) 

## Create a Razor web app

From a terminal, run the following commands:

```console
dotnet new razor -o RazorPagesMovie
cd RazorPagesMovie
dotnet run
```

The preceding commands use [dotnet](https://docs.microsoft.com/dotnet/core/tools/dotnet) to create and run a Razor Pages project.

![Home or Index page](../razor-pages/razor-pages-start/_static/home.png)

[!INCLUDE[razor-pages-start](../../includes/RP/razor-pages-start.md)]

## Open the project

Press Ctrl+C to shut down the application.

From Visual Studio, select **File > Open**, and then select the *RazorPagesMovie.csproj* file.

### Launch the app

In Visual Studio, select **Run > Start Without Debugging** to launch the app. Visual Studio starts [IIS Express](http://www.iis.net/learn/extensions/introduction-to-iis-express/iis-express-overview), launches a browser, and navigates to `http://localhost:port`. Visual Studio launches the first web app at port number 5000 and increments the port number with new applications.

>[!div class="step-by-step"]
[Next: Adding a model](xref:tutorials/razor-pages/model)  