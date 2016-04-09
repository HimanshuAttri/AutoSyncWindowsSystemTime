# Auto_System_Time-Updater_Windows



#Whats The Problem?

When my old laptop's CMOS bios batteries drained on every startup my pc time needs to be up-dated manually.



#Solution

I created a .cmd file of a simple command



w32tm /resync



And scheduled a task to run that .cmd file on every startup because the command needed admin privileges to rum this command.
the updatetime.cmd is included in repository

#How to schedule task ?

go to link

http://windows.microsoft.com/en-in/windows/schedule-task#1TC=windows-7


