# 👤 Person Registration API (.NET 8)

This project is a simple RESTful API built with **.NET 8 and C#**, designed to perform basic CRUD operations (Create, Read, Update, Delete) for managing people data. It's ideal for learning and demonstrating fundamental API architecture using **Entity Framework Core**, **SQLite**, and **EF Core Migrations**.

---

📷 Technology Badges
<p>
<img src="https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/> <img src="https://img.shields.io/badge/C%23-%23239120.svg?&style=for-the-badge&logo=c-sharp&logoColor=white"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/> <img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
</p> 

---

## 🚀 Technologies Used

- [.NET 8](https://learn.microsoft.com/en-us/dotnet/core/whats-new/dotnet-8)
- [C#](https://learn.microsoft.com/en-us/dotnet/csharp/)
- [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/)
- [SQLite](https://www.sqlite.org/index.html)
- [EF Core InMemory](https://learn.microsoft.com/en-us/ef/core/testing/in-memory)
- [Visual Studio Code](https://code.visualstudio.com/)
- Terminal for package management and running commands

---

## 📦 Installed Packages

The main packages were installed via terminal using the following commands:

```bash
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.Sqlite
dotnet add package Microsoft.EntityFrameworkCore.InMemory
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet ef migrations add Initial
dotnet ef database update
````

📝 Notes
This project was developed for educational purposes to demonstrate the basic structure of an API in .NET 8 using modern tools and good practices. It can be extended with authentication, validations, and unit testing.
