# ShopBridge
Demo Site

## Softwares required- 
Visual Studio 2019 and SQL Server

##Steps to run the code
Download code
Open it
Change Connection string to the existing one (Keep conncetion string name and provider similiar, change connection string)
Since, I have used Code First approach, We need to do so steps to create db.
Go to Tools -> Nuget Package Manager -> Package Manager Console
Write some commands, enable migrations  and press Enter
Add-Migration 'First Migration' and press enter
for re-scaffolding, again enter Add-Migration 'First Migration'
After adding migrations, we need to update db. So, write update -database
We ar done with this. Now if we check, the Database should be created as the specified location in the Sql Server
Once done with this, Build and run the appilication. You may get, The site can not be reached. DOnt't worry Just add /swagger to the URL and you will get the list of APIs.
That's it. :-)

Note :- Keep the project in running mode so that we wil be able to get API calls when call API from UI solution.
