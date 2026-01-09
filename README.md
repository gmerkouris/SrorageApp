### Run the Project (Visual Studio 2026)
- Visual Studio 2026
- .NET 10 SDK
- SQL Server

### Steps
1. Clone the repository:
 bash:  git clone -b unitTest https://github.com/gmerkouris/SrorageApp.git

2. Open the solution with Visual Studio 2026: SrorageApp.slnx file
   
4. Install NuGet packages <br>
   -Microsoft.EntityFrameworkCore
   -Microsoft.EntityFrameworkCore.SqlServer
   -Microsoft.EntityFrameworkCore.Tools
    -Microsoft.AspNetCore.Identity.EntityFrameworkCore
    -Microsoft.EntityFrameworkCore.InMemory
    -xUnit
    -xunit.runner.visualstudio

5. Import the database file db.bacpac  from ..\SrorageApp\database\ into SQL SERVER
6. Configure database connection: Update the DefaultConnection value in:  ..\SrorageApp\appsettings.json
7. Build the solution.
8. Start Without Debugging (Ctrl + F5)
9. Test credentials:
   Admin
    -Username: storage@admin.gr
    -Password: Test1234!!!
  User
    -Username: pcbox@pcbox.gr
     -Password: Qwerty123!!!!

10. Run unit tests: Ctrl + R, A
