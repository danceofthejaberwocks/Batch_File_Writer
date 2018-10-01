# Batch_File_Writer
A program to write batch files to correct problems found on switches with Solarwinds
Solarwinds generates reports based on devices that need action that you can then export to excel. 
The goal of this program is to take the information needed from Excel (e.g. ip address) and then create a batch file to telnet 
into the switches that need something fixed and execute the commands on all of them at once. 
I am using telnet because you can not ssh on a batch file that I am aware of. 
