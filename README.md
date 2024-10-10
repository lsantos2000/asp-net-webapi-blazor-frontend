# GameStore - Blazor Frontend

GameStore Frontend is an ASP.NET Core application, using Blazor.

It integrates with a correspondent ASP.NET Web API backend, by the name of GameStore Backend. Check out the backend here: https://github.com/lsantos2000/asp-net-webapi-backend

Both GameStore Frontend and Backend manage a collection of games and genres.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

This solution demonstrates how to build a modern web application using ASP.NET Web API for the backend and Blazor for the frontend. The Web API provides RESTful services, while Blazor offers a rich interactive user interface.

## Features

- ASP.NET Web API backend
- Blazor frontend
- RESTful API endpoints
- Interactive UI with Blazor components

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)

### Installation

1. Clone the repository, both this one (frontend) and the backend:

```sh
git clone https://github.com/lsantos2000/asp-net-webapi-blazor-frontend.git
git clone https://github.com/lsantos2000/sap-net-webapi-backend.git
```

Follow the instructions to get the backend up and running.

2. Navigate to the frontend project directory:

```sh
cd ./asp-net-webapi-blazor-frontend
cd ./GameStore.Frontend
```

3. Restore the dependencies:

```sh
dotnet restore
```

### Usage

1. Build the solution:

```sh
dotnet build
```

2. Run the application:

```sh
dotnet run
```

3. Open your browser and navigate to `https://localhost:5001` to access the Blazor frontend.

### License

This project is licensed under the MIT License.

Code based, and modified for demo purposes, on the source code of the YouTube video "ASP.NET Core Full Course For Beginners" by Julio Casal.

Check out Julio at https://dotnetacademy.io.
Watch the video at https://www.youtube.com/watch?v=AhAxLiGC7Pc and https://www.youtube.com/watch?v=RBVIclt4sOo .
I encourage you to visit the above links and follow the original author.
