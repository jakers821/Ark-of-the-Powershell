# Ark of the Powershell

You are free to use, modify, or do whatever else you like to these examples. My only request is that, if you add any functionality, you commit the changes to this repository. 

Here is a brief description of each of the files. 

ConnectToAnotherWorkstation.ps1
--> This script asks for a computer you'd like to connect to on your domain. Then, after prompting you for credentials, if they are sufficient, it will connect you via PowerShell session with the said workstation. 

Get-StockQuote.ps1
--> This script is from A Powershell Script a Week. "It calls the webservicex stockquote SOAP web service and it returns the result in xml. The xml get parsed into PS object and returned to the user. The user can enter more then one symbol and use the format-table cmdlet for easy comparison of stocks." 

RemoteDesktopConnection.ps1
--> This script opens the Remote Desktop Connection client and allows you to enter the computer you'd like to connect to. 

SeeProcesses.ps1 
--> This script opens up the running processes in the Out-GridView, which is a nice table format. 

TurnOnRemoteRegistry
--> This script enables the Remote Registry service and makes it automatically start. 
