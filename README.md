# ✅ Todo API – ASP.NET Core Web API

A simple Todo List REST API built using **ASP.NET Core Web API** and **Entity Framework Core**, with support for DTOs to hide sensitive fields.

---

## 📁 Project Overview

- **Framework:** ASP.NET Core Web API  
- **Database:** Entity Framework Core with SQL provider  
- **Features:**  
  - CRUD operations  
  - DTO to hide internal fields (`Secret`)  
  - RESTful routing (`/api/TodoItems`)  

---

## 🚀 Getting Started

### 🔧 Prerequisites

- .NET 6 SDK or later
- Visual Studio / VS Code
- Postman or Swagger UI for testing

### 🛠 Setup Steps

```bash
git clone https://github.com/nisung-kerung/Todo-Web-Api
cd Todo-Web-Api

# Optional: If using EF Core migrations
dotnet tool install --global dotnet-ef
dotnet ef migrations add InitialCreate
dotnet ef database update

# Run the app
dotnet run
