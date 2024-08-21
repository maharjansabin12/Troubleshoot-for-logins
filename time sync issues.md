# time sync issues


may encounter various problems, if your clock is out of sync
win uses Kerberos protocol which is time-sensitive causing authentication errors

first run command prompt as administration and type the command: w32tm /query /configuration


###### you need to have port 123 open in firewall configuration

firs open the GP management 

command: gpudate /force
and restart the w32tm service in powershell as administrator

command: <b>restart-service w32time</b>



<img src="https://github.com/maharjansabin12/screenshot/blob/main/time1.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time2.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time3.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time4.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time5.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time6.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time7.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time8.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time9.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time10.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/time11.png" height="80%" width="80%">









