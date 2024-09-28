# GameStore - Blazor

This repository contains a solution that integrates an ASP.NET Web API backend (GameStiore Backend) with a Blazor frontend.

GameStore Backend is an ASP.NET Core application that manages a collection of games and genres. The backend project demonstrates the use of Entity Framework Core for database operations. 

Code based, and modified for demo purposes, on the source code of the YouTube video "ASP.NET Core Full Course For Beginners" by Julio Casal at https://dotnetacademy.io, see https://www.youtube.com/watch?v=AhAxLiGC7Pc.


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
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

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)

### Installation

1. Clone the repository, both this one (frontend) and the backend:
    ```sh
    git clone https://github.com/lsantos2000/asp-net-webapi-blazor-frontend.git
    git clone https://github.com/lsantos2000/sap-net-webapi-backend.git
    ```

    Follow the isntructions to get the bakend up and running.
    
2. Navigate to the frontend project directory:
    ```sh
    cd asp-net-webapi-blazor-frontend
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

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.