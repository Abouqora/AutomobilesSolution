# AutomobilesSolution

Install the following packages from Nuget : 

Microsoft.EntityFrameworkCore.Design
Microsoft.EntityFrameworkCore.SqlServer
Microsoft.EntityFrameworkCore.Tools
Microsoft.Extensions.Configuration
Microsoft.Extensions.Configuration.Json

Right-click on the project, select Open in Terminal. On Developer PowerShell dialog, run dotnet ef command to generate database context
and Car entity model from MyStock database as follows:

 dotnet ef dbcontext scaffold "Server=.;uid=sa;pwd=P@ssword1234;database=MyStock; TrustServerCertificate=True" Microsoft.EntityFrameworkCore.SqlServer --output-dir DataAccess
