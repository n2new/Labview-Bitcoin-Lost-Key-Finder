# Labview Lost Bitcoin -Key-Finder
 Labview Bitcoin Lost Key finder.

Uses Linux  Pipe implementation. Peaks out at 1,065,000 Addresses a second
Benchmark 4X  E7-4830 Processor 50 threads. Uses Address File.
Can search a few Million address Compressed and Uncompressed With no siginificant slow down. 
See Example Bitcoin address File. Also Can notify with Text message. 

Issues

 Current Build Will not save found key file But will copy it to the clip baord. 
 Pipe Data format issues causes loss in 1 in a few thousands lines. Still trying to figure this out. 
 Need to set or automate path to save Found Key file.  Would love some contributers. 

Labview Version 2020 Linux Bitcoin Key finder
Uses Fasy Keygen By Magnuspub with Mod's. 




![Key Finder](https://user-images.githubusercontent.com/36019554/180500126-c5626ea6-956f-4d81-bfd4-71770173cb0f.jpg)


![image](https://user-images.githubusercontent.com/36019554/180504578-4b60d449-202d-447c-a6a3-1f7897ef04b1.png)


Instructions

Keygen needs path Set In source code constant. (Would like to automate this In the future and package release with Keygen).

Unpack all files and sub vi's into a folder.
Open project 
run
Load Search File
Set Path for Keygen.
Copy Keygen to correct Path. 
Select Number of threads. 

Press start. Enjoy! 

Chances of finding Key, Near Zero but this is a fun learning excersise. 


Donate: Bitcoin Address  bc1q7h637v8x62lapknuvlyxzf0ylan38vexc0h6wr


