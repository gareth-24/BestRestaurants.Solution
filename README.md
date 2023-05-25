# Best Restaurants App

#### Web app using C# and SQL to create and display restaurants and cuisines using an SQL database.

#### By Gareth Grindeland & Chris Davila

## Technologies Used

* Git
* C#/.NET version 6.0.402
* MySQL Workbench
* Enity Framework Core version 6.0.0
* HTML & CSS
* Bootstrap version 5.2.3


## Description

## Setup/Installation Requirements

<!-- Going forward, don't forget to include setup instructions in your README for an appsettings.json with a database connection string. -->

## Setup/Installation Requirements

* _Clone this repository to your desktop._
* _Open your shell (e.g., Terminal or GitBash) and navigate to this project's production directory at ```./BestRestM2M.Solution/BestRestaurants/```._
* _Within the production directory "BestRestaurants", create a new file called ```appsettings.json```._
* _Within ```appsettings.json```, put the following code, replacing the "uid" and "pwd" values (in the brackets below) with your own username and password for MySQL. Also replace the "database" value with your database name._
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[DATABASE_NAME];uid=[USERNAME];pwd=[PASSWORD];"
  }
}
```
* _Run the terminal command ```dotnet ef database update``` to create the initial MySQL database._

#### To Run the App in the browser:
* _Navigate to this project's production directory "BestRestaurants"._
* _Run ```dotnet watch run``` in the command line to start the application in development mode with a watcher. This will open the webpage in your browser._
* _To exit out of the application, you can use the keyboard command "CTRL+C" on Mac and Windows._
* _Optionally, you can run ```dotnet build``` within the production directory to compile this app without running it._


## Known Bugs

* _No Known Issues_

## License

_MIT License_

_Copyright (c) 2023 Gareth Grindeland & Chris Davila_
