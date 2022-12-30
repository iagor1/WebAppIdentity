# WebAppMVC with identity
A MVC project created to implement identity on the mvc

# How to run 
1 - clone this repository

2 - you will need SqlServer

3 - change the connection string in appsettings.json to your name of database 
 ```sh
 "ConnectionStrings": {
    "DefaultConnection": "Server=localhost\\SQLEXPRESS;Database=master;Trusted_Connection=True;Trust Server Certificate=true;"
  },
  ```
  *Trust Server Certificate=true; its not mandatory but i was having some issues with the connection and this was the solution*
  
 4 - Open the project on Visual Studio 2022 and run :)
