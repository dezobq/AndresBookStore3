2022-10-22
1042
Create a default ASP.NET Core MVC Application
-Using .NET Core 3.1 LTS
-Individual account Authentication
-Keep the HTTPS default
-Add Razor Runtime

1044
Running this in the lab ... need to comment the JSON file emtry fot the HTTPS
see properties/lauchSettings.json


1047
It works
Checked the Dependency/Packages just-in-cases

1052 Let`s push to GitHub

2022-11-01 

1102 Changed the content inside the bracets (to empty()) in the line 33 
     of the Startup.cs (options => options.SignIn.RequireConfirmedAccount = true)

2022-11-02

1658 Setting up the project - Bootstrap.
1659 I chose the Journal theme from the bootswatch.com ean apled it to to project.
1659 Replaced the bootstrap.css found in wwroot/lib/bootstrap/dist/css.
1701 Replaced the site.css found in the main css folder and replaced it with the provided.
1703 Changed the name of the file bootstrap.min.css to bootstrap.css in the _Layout.cshtml.
1704 Aplied some changes to nav class in the files _Layout.cshtml and _LoginPartial.cshtml.
1706 Added additional properties to the footer class
1707 Added some links to extra css files.
1707 Added 3rd party tools:JQuery UI(Datepicker), DataTables, Sweetalerts, FontAwesome, Toastr.

1707 Tested the new visual elements and its looking good!

1738 Added a dropdown menu . not working - part of the instructions in the powerpoint file is missing.

1743 Adding Projects and Mobility

1744 Added 3 new projects to the application
    - Copied the Data folder from AndresBookStore project to the new project AndresBookStore to the new project .DataAccess
    - Then delete the original data folder


1755 Tried to install the nuGet pacjage but I had the same problem again. It does not work.

1830 Removed the projects added and reversed the data folder to the original folder to try it again.

2022-11-03 

1000 Fixed the dropbox code - working

2022-11-08
1020 - Back to part 1.4 - Adding projects & modify

1025 - Created 3 new projects -> DataAccess, Models and Utility

1031 - Copied the Data folder from AndresBookStore project to the .DataAccess project
       Deleted the original

1035 Issue: When I try to Install the Microsoft.EntityFrameworkCore.Relational and Core.SqlServer packages they don't 
     install and return an error list:
     ------------------------------------------------------------------------------------------------------------------
     ------------------------------------------------------------------------------------------------------------------
     Severity	Code	Description	Project	File	Line	Suppression State
        Error	CS0234	The type or namespace name 'Data' does not exist in the namespace 'AndresBookStore' (are you missing an assembly reference?)	AndresBookStore	C:\Users\dezob\Source\Repos\dezobq\AndresBookStore\AndresBookStore\Startup.cs	1	Active

        Error	CS0246	The type or namespace name 'ApplicationDbContext' could not be found (are you missing a using directive or an assembly reference?)	AndresBookStore	C:\Users\dezob\Source\Repos\dezobq\AndresBookStore\AndresBookStore\Startup.cs	30	Active

        Error	CS0246	The type or namespace name 'ApplicationDbContext' could not be found (are you missing a using directive or an assembly reference?)	AndresBookStore	C:\Users\dezob\Source\Repos\dezobq\AndresBookStore\AndresBookStore\Startup.cs	34	Active

        Error		    Package restore failed. Rolling back package changes for 'AndresBooks.Utility'.				

        Error	NU1202	Package Microsoft.EntityFrameworkCore.Relational 7.0.0 is not compatible with netcoreapp3.1 (.NETCoreApp,Version=v3.1). Package Microsoft.EntityFrameworkCore.Relational 7.0.0 supports: net6.0 (.NETCoreApp,Version=v6.0)	AndresBooks.Utility	C:\Users\dezob\Source\Repos\dezobq\AndresBookStore\Utility\AndresBooks.Utility.csproj	1	
    ------------------------------------------------------------------------------------------------------------------
    ------------------------------------------------------------------------------------------------------------------
    Solution: No solution found.

    1145 After many atempts to find out the real problem we decided to restart from the begining the project
         keeping only the README.txt records from the older version.

2022-11-09 

1900 Renamed the older repository as AndreBookStore-first in the github and local.

1907 Created the project from zero again:
        -Using .NET Core 3.1 LTS
        -Individual account Authentication
        -Keep the HTTPS default
        -Add Razor Runtime

1911 Commented the Properties/launchSttings.json to run the project in the lab sessions.


1914 Tested and working as expected.

1935 Started the bootstrap changes

1935 Decided to change the previous template (Journal) to the Vapor template fount at bootswatch.com

1939 Replaced the css files bootstrap.css and site.css

1950 Changes aplied to layout.cshtml and LoginPartial.cshtml
     Tested and working

1951 Added additional scripts and styleseets for 3rd party tools.

1955 Added Drop-down menu.
        
1959 Tested and working


2000 Added 3 new projects
        -DataAccesss
        -Models
        -Utility

2001 Copied the Data folder from the original project and pasted into the new project DataAccess. Deleted the original.

2020 Deleted the migrations folder from the .DataAccesss/Data

2023 Changed the namespace name at Startup.cs file

2030 Deleted the Class1.cs from all the projects

2022-11-10 

1034 Like in the first try the projects start failing when I try to install the nuget packages (EntityFrameWork.Relational and SQL server.)

1100 Moved Models folder to AndresBooks.Models. Deleted original

1101 Modified the error.cshtml at Views/Shared

1104 Added project reference to .DataAcces and .Models


1106 Renamed the Models folder to View Models


2022-11-14

1850 Moved the project from the OneDrive folder to the local machine.

1900 Unfortunatly I can't go ahead without the solve these problems.


