## DatabaseFirstNorthwind ##

This project demonstrates how to setup the RadEntityFrameworkCoreDataSource along with the RadGridView and RadDataPager to display the
data from the NorthWind database. If you don't have it setup, you can follow these steps:

1. Open SQL Server Management Studio and connect to your sql server. 
2. Open the Package Manager Console(https://docs.microsoft.com/en-us/nuget/consume-packages/install-use-packages-powershell) in Visual Studio.
3. Type Update-Database and hit Enter.


Note, that you may need to update the connection string inside the OnConfiguring method in the NorthwindContext class. 


<keywords:databasefirst, entityframeworkcore>