# Auto_System_Time-Updater_Windows



#Whats The Problem?

When my old laptop's CMOS  batteries drained on every startup my pc time needs to be updated manually. Major problem with wrong time and date is chrome does not allow https usage and shows <strike>https</strike> as shown below.

![cert_error_chrome-600x361](https://cloud.githubusercontent.com/assets/12981490/14410719/16a72196-ff53-11e5-9aef-5a997977aa34.png)





#Solution

I created a .cmd file containing following command



w32tm /resync



And I just scheduled a task to run that .cmd file on every startup because the command needed admin privileges to run this command.
the updatetime.cmd is included in repository

#How to schedule task ?

go to link

http://windows.microsoft.com/en-in/windows/schedule-task#1TC=windows-7

and it works well unless you have a net connection.


