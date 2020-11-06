# What is our project about?
---
Our project is about finding lost things. Lost and found items retrieval process is one of the major problems which needs further 
development. Traditional way of reporting for lost or found items requires a great deal of both time and effort. Consequently, 
citizens are hesitant in reporting such items due to the complex and prolonged procedure, with authorities required to expend 
many work hours in attempts to provide a hasty response to such reports. 

So, we have made a new approach to improve the lost and found items reporting procedure with our website. This website offers a 
user-friendly form for reporting items’ with the feature of easy pinpointing to lost or found items. User can give necessary 
information of the lost or found item here. Users don't even need to search manually for items because our system automatically detects
matched item from database and provide necessary contacts. 

# Features :
---
Features that we have implemented are given below:
1. New User sign up
1. Existing user log in
1. User can view his profile
1. User can update his profile
1. User can report about lost items
1. User can report about found items
1. User can view his history of lost and found items
1. User can view each report separately in details
1. User can delete any of his previous reports
1. User can view the result of his reports and get the contacts of matched user


## Member’s Contributions :
---
*Member 1 :* 
Name: MD. Abu Yousuf Sajal
Id: 170104025
Role: Front-End

_Frontend Technologies:_ 
Framework : Bootstrap, Fontawesome
Design Pattern : Responsive
Structure Language : HTML5
Styling Language : CSS
Functional Language : Javascript

*Member 2 :* 
Name: Syed Rifat Manjur
Id: 170104026
Role: Back-End

_Backend Technologies:_ 
Framework: ASP.NET, Entity Frame Work
Design Pattern: MVC
Programming Language: C#
Query Languages: LINQ, MSSQL


## Instruction to follow for running the project :
---
At first you need to install
1. Visual Studio 2019
1. SQL Server 2014 Management Studio

### For connecting to database, do the following :

1. Copy and Paste FindLostThings.mdf and FindLostThings_log.ldf file to the location 
C:\Program Files\Microsoft SQL Server\MSSQL12.SQLEXPRESS\MSSQL\DATA or your installed location.
1. Open Microsoft SQL Server Management Studio. You will see a dialog box "Connect to Server". Here, you will see your server name.
Copy your server name before clicking connect. example: DESKTOP-D3OV9OU\SQLEXPRESS.
1. Right click on Database. click Attach. Click Add. Select FindLostThings.mdf. Click OK. Click OK.
1. Open the project in Visual Studio 2019. In Web.confiq file, go to the tag <connectionString>. Here, you will find
data source=DESKTOP-D3OV9OU\SQLEXPRESS. Replace the server name with your server name that you copied.

Database connection is completed! Now, run the he project and enjoy all our interesting features!

