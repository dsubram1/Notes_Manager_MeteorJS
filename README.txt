Meteor Setup and installation:

Installation on Windows:
 
1. 	First Install Chocolatey
        	Install with cmd.exe and Run the following command:
 
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
 
      2. Run this command using an Administrator command prompt:
 
choco install meteor
 
Installation on Mac:
1. 	Run the following command in your terminal to install the latest official Meteor release:
 
curl https://install.meteor.com/ | sh

Creating Project:
 
Move to the project folder and create a meteor project using the command:
 
meteor  create <projectname> 
 
The application runs on port 3000 by default. Run the project using the command
 
meteor
 
Install a frontend framework such as Materialize. Move to the project directory and use the command
 
meteor add materialize:materialize

We are using the following versions: 
Meteor 1.6.1
materialize-css 0.100.2
