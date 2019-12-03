![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# 如何卸载SQL Server Instance
#### How To Uninstall an SQL Server Instance

## Contents

- [中文](#中文)
- [English](#English)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


How to uninstall an SQL Server Instance from a mulit-instance Database Server.
如何从mulit-instance Database Server卸载SQL Server Instance。
Step 1:
From the Database Server go to StartàRun, and type in appwiz.cpl.
步骤1：
从数据库服务器转到StartàRun，然后键入appwiz.cpl。

![#](images/01-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
Step 2:
Locate the Database Server product you would like to uninstall. In this case we are selecting ‘Microsoft SQL Server 2014 (64-bit)’, and click ‘Uninstall/Change’.
步骤2:
找到要卸载的Database Server。在这案例中，我们选择“Microsoft SQL Server 2014（64位）”，然后单击“Uninstall/Change”。

![#](images/02-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
Step 3:
Click ‘Remove’.
步骤3:
单击“Remove”

![#](images/03-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
Be patient while the uninstall process begins…

![#](images/04-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
Step 4:
Select the Instance you wish to remove. In this case we are removing the SQL instance SQLSHARE09.
Click ‘Next’.
步骤4:
选择你想要删除的Instance，在这个案例中，我们将删除SQL实例SQLSHARE09。
单击“Next”。

![#](images/05-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
Step 5:
Select the Instance SQLSHARE09, and it’s services:
Database Engine Services
Reporting Services – Native
DO NOT select Shared Features.
Click ‘Next’.
步骤5:
选择Instance SQLSHARE09及其服务：
Database Engine Services
Reporting Services – Native
请勿选择Shared Features。
单击“Next”。

![#](images/06-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
Step 6:
Click ‘Remove’.
步骤6:
单击“remove”

![#](images/07-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
Step 7:
Click ‘Close’.
步骤7:
单击“close”

![#](images/08-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
You are done.
To confirm…
Check the Configuration Manager, or check under Services.
SQL Server Configuration Manager:
Simply open up the ‘SQL Server Configuration Manager’, and ensure the SQL Server Instance SQLSHARE09 is nolonger listed.
完成。
需确认：
检查Configuration Manager，或在“Services”下查看。
SQL Server Configuration Manager:
只需打开“SQL Server Configuration Manager”，并确保不再列出SQL Server Instance：SQLSHARE09。

![#](images/09-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
The service name should not appear in the list. Here we see the service is missing therefore it has been successfully removed.
服务名称不应出现在列表中，在这里，我们看到服务丢失，因此表示已成功删除。

![#](images/10-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 
Services:
StartàRun: Services.msc
服务：
StartàRun：Services.msc

![#](images/11-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")

 
Look to see if the SQL Server (SQLSHARE09) Services is listed at all. All Database Services for SQLSHARE09 will not be present in the services list.
查看是否列出了SQL Server（SQLSHARE09）Services ：SQLSHARE09。它的Database Services都不会出现在服务列表中。

![#](images/12-How-To-Uninstall-an-SQL-Server-Instance.png?raw=true "#")
 

[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

