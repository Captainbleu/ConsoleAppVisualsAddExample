---
title: Presentation
author: Yann M. Vidamment (MorganKryze)
description: The Presentation project serves the purpose to demonstrate the capabilities of the library gathering the major features in a single application.
keywords: c#, documentation, presentation
ms.author: Yann M. Vidamment (MorganKryze)
ms.date: 03/31/2024
ms.topic: tutorial
ms.service: ConsoleAppVisuals
---

# Presentation

|                    Author                     |  Size  | Library version |                                       Source files                                       |
| :-------------------------------------------: | :----: | :-------------: | :--------------------------------------------------------------------------------------: |
| [MorganKryze](https://github.com/MorganKryze) | medium |     latest      | [link](https://github.com/MorganKryze/ConsoleAppVisuals/blob/main/examples/Presentation) |

## Introduction

The Presentation project serves the purpose to demonstrate the capabilities of the library gathering the major features in a single application.

![Demo](../assets/vid/gif/presentation.gif)

## Features covered

The project covers the following features:

- General: Change `Title` font, update elements, menus management
- PassiveElements: `Title`, `Header` & `Footer`, `Matrix`, `TableView`
- InteractiveElements: `ScrollingMenu`, `Dialog`, `Prompt`, `IntSelector`, `TableSelector`
- AnimatedElements: `FakeLoadingBar`, `LoadingBar`
- Inspector PassiveElement: `ElementDashboard`, `ElementsList`

## Build & Run

### Install

To clone the project, run the following command:

```bash
git clone https://github.com/MorganKryze/ConsoleAppVisuals.git
```

Or alternatively, download the project as a zip file from the [repository](https://github.com/MorganKryze/ConsoleAppVisuals).

### Setup

#### Versions

The project is built with the latest version of the library.

The project is built with the `net9.0` and `net8.0` target framework. Some changes should be applied to the project to make it compatible with the `net6.0` or `net7.0` target frameworks.

Check your local .NET SDK version by running the following command:

```bash
dotnet --version
```

#### Build

To build the project, open a terminal in the project directory (`./ConsoleAppVisuals`).

Then move to the working directory:

```bash
cd examples/Presentation
```

Finally, run the following command:

```bash
dotnet build
```

### Run

If the build is successful, run the following command:

```bash
dotnet run
```

The application should start and display the same result as in the demonstration video.

---

Have a question, give a feedback or found a bug? Feel free to [open an issue](https://github.com/MorganKryze/ConsoleAppVisuals/issues) or [start a discussion](https://github.com/MorganKryze/ConsoleAppVisuals/discussions) on the GitHub repository.
