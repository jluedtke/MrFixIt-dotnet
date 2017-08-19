### Mr Fix-It
#### A repair technician job service.

COMPLETED:
* Users can register and log on
* Users may sign up to be "workers" on the site.
* New jobs may be added to the jobs list.
* A job can be assigned to a worker.
* A worker may take on mulitple jobs from the Worker Dashboard.

IN PROGRESS
* Make *claiming* a job an **AJAX** action.

NEXT UP
* A worker may designate one **active** job at a time. **AJAX**
* Workers may mark jobs complete, and select a new active job. **AJAX**


# Mr Fix-It
### Jared Luedtke 08.18.2017

## Description
A repair technician job service.

## Specs
| Spec | Input | Output | Description |
| :------------- | :------------- | :------------- | :------------- |
| Users can register and log on | Log In | Welcome, User1 | Program needs to implement user authentication |
| Users may sign up to be "workers" on the site. | "Create worker account" | Worker1 | Program creates workers to help regular users. |
| New jobs may be added to the jobs list. | "Job1" | Job1 | Program is designed around this feature for buisiness. |
| A job can be assigned to a worker. | Job1 | Worker1 => Job1 | Program is designed around this feature for buisiness. |
| A worker may take on mulitple jobs from the Worker Dashboard. | Job2 | Worker1 => Job1, Job2 | People tend to work on mutliple things at a time. |
| Worker's claim jobs without being redirected to a new page. | Job1 | Worker1 => Job1 | Ease of use for both workers and users |
| A worker may designate one **active** job at a time. | Job1 | Worker1 => Job1 (A), Job2  | Let's the users know if their problem is being handled while the workers can focus more clearly on specific repairs. |
| Workers may mark jobs complete, and select a new active job. | Job1 (C) | Worker1 => Job1 (C) | Let's the users know if their problem is being handled while the workers can focus more clearly on specific repairs. |


## Setup/Installation Requirements
1. Clone this repository : [GitHub](https://github.com/jluedtke/MrFixIt-dotnet)
2. Make sure you have [Visual Studio 2015](https://www.visualstudio.com/downloads/) and [SQL SSMS](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms) installed
3. Execute the file "MrFixIt.mvss" in Project Directory
4. Open Windows Powershell and navigate to MrFixIt/src/MrFixIt
5. Input the command: dotnet ef database update
6. This will set up a blank database.
7. Inside of Visual Studio, click "IIS Express" or the green play button to start the webpage.

## Known Bugs
Web page can look a little funky when marking Active and Unactive repairs

## Technologies Used
* .NET Core
* C#
* Tuxedo

## Legal
Copyright (c) 2017 **_Jared Luedtke_** All Rights Reserved.
Licensed under the MIT license.