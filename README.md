# NL Jobs WebApp

![ASP.NET Core MVC](https://img.shields.io/badge/ASP.NET_Core_MVC-5C2D91?logo=.net)
![Entity Framework Core](https://img.shields.io/badge/Entity_Framework_Core-512BD4?logo=.net)

A job posting web application built with ASP.NET Core MVC for managing and searching job listings.

## Features

- **Job Listings Management**
  - Create, read, update, and delete job postings
  - Responsive design with Bootstrap
  - Search functionality

- **User Authentication**
  - Role-based authorisation
  - Protected admin operations

## Getting Started

### Prerequisites

- [.NET 6.0 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or VS Code
- SQL Server (or SQLite for development)
- 
### Folder Structure

  NL_JobsWebApp/
├── Controllers/
│   └── JobsController.cs       # Job CRUD operations
├── Models/
│   └── Job.cs                  # Job model
├── Views/
│   ├── Jobs/
│   │   ├── Index.cshtml        # Job listings
│   │   ├── Create.cshtml       # Create form
│   │   └── ShowSearchForm.cshtml # Search UI
└── Data/
    └── ApplicationDbContext.cs # Database context
