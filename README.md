# SampleWebApp

Sample web application for technical test for Archer Logic Pte Ltd.

## Assumptions

* Profile images cannot exceed more than 5 mb in size.
* Web Application will be hosted on a private network, and only administrators will have access to this web application.

### Softwares Used

Worked on a clean PC. Unfortunately, did not have much time to improve on the cosmetic part of the application...

```
Visual Studio 2019
SQL Server Express 2019
```

### Running the program

Steps to run the program:

```
1) Unzip SalonZSample.zip file to a folder used by Visual Studio 2019 to save projects in.
```

```
2) Create database in SQL Server Express 2019.
```

```
3) Locate the 'appsettings.json' file in the unzipped folder, and change database name to the database created in (2).
```

```
4) Run Program.
```

The tables will be automatically created in the process of running the application.

## Unit Testing

Sorry, there is no unit testing available..

## Deployment

This application uses DotNetCore 2.2 as its framework, thus you would need to download .NetCore hosting bundle (which includes the .NET Core Runtime and IIS support) to deploy it to localhost.

## Technologies Used

* ASP.Net Core MVC

## Authors

* **Alvin Loh** - *Developer*

