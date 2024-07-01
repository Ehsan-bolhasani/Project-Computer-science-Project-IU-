Installation and Run Instructions
System Requirements
Operating System: Windows 10 or later
RAM: 4GB or more
Disk Space: 500MB or more
Prerequisites
Before setting up the project, ensure that the following software and tools are installed:

Visual Studio (with .NET development workload)
SQL Server
SQL Server Management Studio (SSMS)


Installation Steps
 1- Set up the Development Environment:
Install Visual Studio and ensure the .NET development workload is selected during installation.
Install SQL Server and SQL Server Management Studio (SSMS).

2-Create a New ASP.NET Project:
Open Visual Studio.
Select File > New > Project.
Choose ASP.NET Web Application template.
Name your project and choose a location to save it.

3-Select Project Options:
In the project template wizard, select Web Forms.
Configure Authentication as required.

4-Creating a SQL Database:
Open SSMS and connect to your SQL Server instance.
Create a new database by running an SQL script or using the graphical interface.
Ensure the database is created locally and note the database name.


5-Connection String Configuration:
Open the web.config file in your ASP.NET project.
Add or update the connection string to match your SQL Server instance details:

<connectionStrings>
    <add name="DefaultConnection" connectionString="Server=YOUR_SERVER_NAME;Database=YOUR_DATABASE_NAME;User Id=YOUR_USERNAME;Password=YOUR_PASSWORD;" providerName="System.Data.SqlClient" />
</connectionStrings>


6-Extract Project Files:
Unzip the Inventory-Management-System.zip file and place the contents in your project directory.
Unzip the packages.zip file and place the contents in the appropriate directory within your project.


7-Creating Models or SQL Tables:
Decide on the database structure and create tables, stored procedures, views, etc. as needed.
Ensure that the necessary SQL scripts are executed to set up the database schema.

8-Write ASP.NET Code:
Develop the functionality of the program by creating models, controllers, and views.
Use the data access layer to interact with the SQL database.


9-Testing and Debugging:
Run the program by pressing F5 in Visual Studio.
Test the application's performance and functionality.
Use Visual Studio's debugging tools to troubleshoot any issues.



Running the Application
1-Open Visual Studio and load the project file.
2-Transfer the packages:
Copy the contents of the packages.zip to the packages directory in your project folder.
3-Update Connection Strings:
Ensure that the connection string in the web.config file matches your local SQL Server instance details.
4-Run the Application:
Press F5 to build and run the project in Visual Studio.


Login Credentials
Username: Admin
Password: 123456


Troubleshooting Tips
Ensure that SQL Server is running and accessible.
Verify that the connection string in web.config is correctly configured.
Check for any missing packages or dependencies and restore them using NuGet Package Manager.

Thank you for your time and consideration .
All the best.
