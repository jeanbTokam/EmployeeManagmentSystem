Employee Management System

This project is an Employee Management System built using Web API, Blazor, Web Assembly, and SQL Server. 
It allows you to efficiently manage employee data within an organization.

  Setup Instructions.

    Prerequisites
    
            •	Visual Studio 2019 or later
            •	.NET 5 SDK
            •	SQL Server Management Studio (SSMS) or any SQL Server client tool
            
    Steps
            1.	Clone the Repository
                     git clone https://github.com/your-username/employee-management-system.git 
            2.	Open Solution in Visual Studio
                •	Navigate to the cloned repository and open the solution file (EmployeeManagementSystem.sln) in Visual Studio.
            3.	Set up the Database
                •	Open SQL Server Management Studio (SSMS) or any SQL Server client tool.
                •	Execute the SQL scripts provided in the DatabaseScripts folder to create the necessary database schema and seed initial data.
            4.	Configure Connection String
                •	Open the appsettings.json file in the EmployeeManagementSystem.Server project.
                •	Update the connection string to point to your SQL Server instance.
            5.	Build and Run the Application
                •	Set both EmployeeManagementSystem.Server and EmployeeManagementSystem.Client as startup projects.
                •	Press F5 or click on the "Start" button in Visual Studio to build and run the application.
            6.	Access the Application
                •	Once the application is running, open your web browser and navigate to the specified URL (usually https://localhost:port/).
            7.	Use the Application
                •	You can now start managing employees through the web interface. Use functionalities such as adding, editing, and deleting employee records.
              
    Technologies Used
    
                •	Web API: Provides the backend services for data manipulation.
                •	Blazor: Facilitates building interactive web UIs using C# and .NET.
                •	Web Assembly: Enables running .NET code directly in the browser.
                •	SQL Server: Manages the database to store employee information.
            
    Contributors
                •	Your Name

License
This project is licensed under the MIT License.

