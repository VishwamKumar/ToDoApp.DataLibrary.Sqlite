
## Helpful Tips
-Add ToDoApp.DataLibrary.Sqlite project into this solution
-If you do want to do a clean run, you can run the following for example

dotnet tool update --global dotnet-ef 
dotnet ef migrations add InitialCreate --project D:\GitHub\ToDoApp.DataLibrary.Sqlite --startup-project D:\GitHub\Vishwam.RestApi.ArchStyles
dotnet ef database update --project D:\GitHub\ToDoApp.DataLibrary.Sqlite --startup-project D:\GitHub\ToDoApp.RestApi.Controllers