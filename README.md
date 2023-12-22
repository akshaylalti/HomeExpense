# HomeExpense Calculator

[![Build Status](https://travis-ci.org/yourusername/homeexpense-calculator.svg?branch=main)](https://travis-ci.org/yourusername/homeexpense-calculator)

A simple HomeExpense calculator web application built using Angular for the front end, ASP.NET Core for the backend, and SQL Server for data storage.

## Features

- Track and manage your home expenses
- User-friendly interface
- Angular for a responsive and dynamic front end
- ASP.NET Core for a robust and scalable backend
- SQL Server for secure and efficient data storage

## Prerequisites

Make sure you have the following installed before running the application:

- Node.js and npm
- Angular CLI
- .NET 5 SDK
- SQL Server

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/homeexpense-calculator.git
   cd homeexpense-calculator
   ```

2. Set up the Angular front end:

   ```bash
   cd ClientApp
   npm install
   ng build
   ```

3. Set up the ASP.NET Core backend:

   ```bash
   cd ..
   dotnet restore
   dotnet build
   ```

4. Configure the database connection in `appsettings.json`:

   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=HomeExpenseDb;Trusted_Connection=True;"
   }
   ```

5. Apply migrations to create the database:

   ```bash
   dotnet ef database update
   ```

6. Run the application:

   ```bash
   dotnet run
   ```

Visit `http://localhost:5000` in your browser to access the HomeExpense calculator.

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Angular, ASP.NET Core, and SQL Server communities for their excellent tools and frameworks.
