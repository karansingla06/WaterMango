# WaterMango
Stack: .NET5, Angular 11, MSSql

Used Visual Studio 2019, Visual studio Code, MS Sql Server 2019 Express <br>

STEPS-

Extract the WaterMangoProject.zip folder

To run frontend app-<br> 
```cd WaterMangoUI``` <br>
```npm i``` <br>
```ng serve --o```


To run backend app-
1. ```cd WaterMangoApi```
2. Open the WaterMango.csproj in Visual studio
3. setup initial db and run migrations-
Go to Nuget Package Manager Console -> <br>
```Update-Database```
2. Build solution and Run the app


visit http://localhost:4200/ and enjoy watering the mango plants :)

