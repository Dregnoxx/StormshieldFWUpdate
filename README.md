### Stormshield Firewall Updater

This PowerShell script, is provided as-is, with no warranty or support.
Created by Dregnoxx:
[Dregnoxx.tech](https://dregnoxx.tech) 
[@dregnoxx](https://twitter.com/dregnoxx).

# Requirements
- [WinSCP](https://winscp.net/eng/download.php)
- [Posh-SSH](https://github.com/darkoperator/Posh-SSH) (Install using `Install-Module -Name Posh-SSH`, in a Powershell window)
- Your root folder should look like this:
  ![image]([https://github.com/Dregnoxx/StormshieldFWUpdate/assets/40840621/80bea1e9-43c7-4498-b49c-b2b5042d8178](https://github-production-user-asset-6210df.s3.amazonaws.com/40840621/315218810-693bdb53-47a9-48c7-b29c-f84b6f5cea7a.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240321%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240321T085257Z&X-Amz-Expires=300&X-Amz-Signature=20234f3fae6da48f4da788fd1bcdcc6e64f0f31f6480e61f2d67ffdaa8bd0c9e&X-Amz-SignedHeaders=host&actor_id=40840621&key_id=0&repo_id=775344505))


# Compatibility
This script is designed for SN160 ,200, 210, 220, 310, 320, 510, and 710 series. It has not been tested on other models.

# Installation
In your Task Manager create a new task, add the name, planify when you want to execute it, and in action specify:
-  Start a program:  `%SystemRoot%\system32\WindowsPowerShell\v1.0\powershell.exe`
-  In argument add:  `-file C:\YOURROOTFOLDER\SN210.ps1 -User USERNAME -PSWD PASSWORD -IP 1.2.3.4 -Client CLIENT_NAME`
