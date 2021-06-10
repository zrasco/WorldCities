# WorldCities

Base .NET 5 project with Angular 11. From The Book "ASP..NET Core 5 and Angular - Fourth Edition"

Changes from default .NET base project:
- Cache-control set in Startup.cs, appsettings.*.json
- Deleted WeatherForecast.cs and Controllers/WeatherForecastController.cs
- /ClientApp/package.json updated to Angular 11 libraries
- /ClientApp/src/app/app.module.ts edited to remove count & weather forecast stuff
- /ClientApp/src/app/nav-menu/nav-menu.component.html to remove count & weather forecast stuff
- Count & wether forecast folders deleted
- Added dedicated AppRoutingModule in app-routing.module.ts and set reference to it in app.module.ts
