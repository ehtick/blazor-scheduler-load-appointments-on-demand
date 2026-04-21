# Blazor Scheduler - Load Appointments On Demand

A quick start project that demonstrates how to efficiently load appointments on demand in the Blazor Scheduler component, optimizing performance by fetching data asynchronously when needed rather than loading all appointments upfront.

## Project Overview

This project showcases best practices for implementing on-demand data loading in the Syncfusion Blazor Scheduler. It demonstrates how to integrate the scheduler with a SQL Server database using Entity Framework Core and handle CRUD operations with load-on-demand functionality. This approach significantly improves application performance by reducing initial data loads and network traffic.

## Prerequisites

* Visual Studio 2022
* .NET 6.0 or later
* SQL Server Database Tools
* Syncfusion Blazor Scheduler NuGet package

## Key Features

* On-demand appointment loading from SQL Server database
* Efficient data retrieval using Entity Framework Core
* RESTful API integration with the Scheduler component
* Database migration setup using EF Core migrations
* CRUD operations support for appointments

## How to Run the Project

1. **Checkout** this project to a location in your disk
2. **Open** the solution file using Visual Studio 2022
3. **Restore NuGet packages** by rebuilding the solution
4. **Apply database migrations** using the Package Manager console:
   ```
   PM> update-database
   ```
   Migrations automate the creation of database based on the model. The required EF Core packages are added with the .NET Core project setup.
5. **Run** the project

## Documentation

For more information, refer to the following Syncfusion Blazor documentation:

* **Introduction**: https://blazor.syncfusion.com/documentation/introduction
* **Schedule Component**: https://blazor.syncfusion.com/documentation/schedule/getting-started
* **Load on Demand**: https://blazor.syncfusion.com/documentation/scheduler/data-binding#load-on-demand

## Support

If you have any questions or need assistance, please refer to the official Syncfusion support channel or documentation.
