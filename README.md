# E-Commerce-Shopping-Website-ASP.NET-CORE

ITA🇮🇹 version

This is a simple e-commerce web application built with **ASP.NET Core** in italian, simulating an online cocktail shopping experience.

## 🛍️ Features

- Browse a list of cocktail products
- Add products to the shopping cart
- Fill in personal data and place an order
- Intelligent product suggestions using **Confidence** logic (association of related products)
- Admin panel to:
  - View all customer orders
  - View sales statistics
  - Add, update, or delete products

## 🔧 Development Environment

- Developed using **JetBrains Rider**
- The solution may also be opened in **Visual Studio 2022 or later**, provided that:
  - You have the necessary .NET SDK installed
  - MySQL-related NuGet packages are installed

## 🧩 Required NuGet Packages

Make sure to install the package for MySQL support

Alternatively, if you used a different package (e.g. MySql.EntityFrameworkCore), adjust accordingly.

🔑 Admin Login

To access the admin area, use the following credentials:

Username: admin  
Password: admin

⚠️ Important: Before running the project, make sure to configure your own MySQL database connection.

Update database settings

Open the appsettings.json file and replace the DefaultConnection string with your actual MySQL configuration:

"ConnectionStrings": {
  "DefaultConnection": "server=localhost;port=3306;database=your_db_name;user=your_user;password=your_password;"
}

📦 Technologies Used
	•	ASP.NET Core MVC
	•	Entity Framework Core
	•	MySQL (via Pomelo.EntityFrameworkCore.MySql)
	•	Bootstrap (for UI styling)
	•	LINQ (for querying and recommendation logic)

📁 Project Structure

E-Commerce-Shopping-Website-ASP.NET-CORE/
│
├── Controllers/           # MVC controllers
├── Models/                # Data models
├── Views/                 # Razor views (HTML UI)
├── wwwroot/               # Static files (CSS, JS, images)
├── Data/                  # DB context and seeders
├── appsettings.json       # Configuration file
└── Program.cs / Startup.cs

📄 License

This project is created by [Angelo Li] for educational purposes only
