# Run MS SQL Server on MacOS

Follow these instructions to run Microsoft SQL Server on a Mac!

## Download Docker Desktop for Mac

https://docs.docker.com/docker-for-mac/install/

Make sure that you have the Docker cli installed.
 
Type "docker version" in the command line into the terminal to check.
 
It should look like this:

![Docker_Version](./Assets/Docker_Version.png)
 
## Install the Linux Version of SQL Server

Replace Username with your Username and TypeYourPassword with your password:

![MSSQLLinuxInstall](./Assets/MSSQLLinuxInstall.png)

Then install the sql cli:

![SQLCLIInstall](./Assets/SQLCLIInstall.png)

## Download and install Azure Data Studio for Mac

https://docs.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio

Then log in using the username and password you set when you downloaded SQL Server:

![AzureServerConnect](./Assets/AzureServerConnect.png)

Click on Advanced Properties and enter the port you created (1433): 

![AzureAdvancedPort](./Assets/AzureAdvancedPort.png)

## Formatting Connection Strings in Visual Studio

![ConnectionString](./Assets/ConnectionString.png)