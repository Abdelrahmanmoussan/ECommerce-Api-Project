# E-Commerce API Project

## Overview

This project is a backend RESTful API for an e-commerce system developed using **ASP.NET Core**. It provides endpoints for managing products, users, orders, and more — making it suitable for integration with a frontend client like a web or mobile app.

## Technologies Used

- ASP.NET Core Web API
- C#
- Entity Framework Core
- SQL Server (or other RDBMS)

## Features

- Product Management (CRUD)
- User Authentication (can be added using JWT)
- Order Creation and Tracking
- Cart Functionality
- API Routing and Controller Architecture

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Visual Studio](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/)
- SQL Server or localdb for database

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Abdelrahmanmoussan/ECommerce-Api-Project.git
   cd ECommerce-Api-Project
Open the solution:

Open ECommerce.sln in Visual Studio.

Set up the database:

Configure your appsettings.json with your database connection string.

Run EF Core migrations (if applicable):

bash
Copy
Edit
dotnet ef database update
Run the project:

bash
Copy
Edit
dotnet run
Visit https://localhost:{port}/swagger to explore and test the API using Swagger UI.

Folder Structure
ECommerce.API/Controllers – API endpoints

Models – Entity models

Data – DbContext and EF Core setup

Services – Business logic (if added)

Future Enhancements
JWT Authentication

Role-based Authorization

Product search and filtering

Order history and reporting

API versioning and documentation
