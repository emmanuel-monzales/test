# BCTech Employee Management (sample)
Small Razor Pages employee management app (.NET 8) using Bootstrap + DataTables and a simple REST API for CRUD.

## Quick setup
Prerequisites:
- Visual Studio 2022
- Microsoft SQL Server Management Studio

Steps:
1. Restore the database
   - Restore the database with the .bak file provided
2. Update connection string inside the appsettings.Development.json
   - Make sure the Database name matches the restored database (`db_BCTech` by default).
3. Run the app
   - Open the solution in Visual Studio 2022 and run (F5
   - If the database is not available the UI will show a clear message instructing to restore the .bak and update the connection string.
     
## Contact
Author: Emmanuel Monzales | emmanuelmonzales.it@gmail.com
