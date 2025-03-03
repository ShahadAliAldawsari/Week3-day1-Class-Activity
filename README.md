<h1>Employee Management System</h1>
<h2>Overview</h2>
This is an ASP.NET Core MVC project that simulates a simple Employee Management System. It allows users to perform CRUD (Create, Read, Update, Delete) operations on employees using Entity Framework Core with a SQL Server database.
<br>
<h2>Features</h2>
- List all employees<br>
- Add a new employee<br>
- Edit employee details<br>
- Delete an employee<br>
- View employee details<be>

<h2>Technologies Used</h2>
- ASP.NET Core MVC (.NET 8/9)<br>
- Entity Framework Core (EF Core)<br>
- SQL Server (Database Management)<br>
- Razor Views (for UI rendering)<br>
- Bootstrap (for styling)<be>

<h2>Project Structure</h2>
/EmployeeManagement<br>
│-- Controllers<br>
│   ├── EmployeeController.cs<br>
│-- Models<br>
│   ├── Employee.cs<br>
│-- Views<br>
│   ├── Employee<br>
│   │   ├── Index.cshtml<br>
│   │   ├── Create.cshtml<br>
│   │   ├── Edit.cshtml<br>
│   │   ├── Delete.cshtml<br>
│-- Data<br>
│   ├── ApplicationDbContext.cs<br>
│-- Program.cs<br>
│-- appsettings.json<br>
