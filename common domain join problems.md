# common domain join problems
so when joining a domain there has to be two criteria to be met

1. there has to be a TCPIP communications path between win 11 machine and DC
2. perform DNS resolution within ADDS and check it is within DNS of AD

now first ping the DC ip address then again ping with the DC name associated with it. <b>ping dc1.abc.com</b> if it reply with same ip thats good but it reply with different ip then first try <b>ipconfig /flushdns</b> then check the dns of the machine with <b>ipconfig /all</b> and if the DNS server ip is not same as of DC then change the DNS server ip address by going into ehthernet setting: <b>WIN+R>ncpa.cpl</b>

<img src="https://github.com/maharjansabin12/screenshot/blob/main/joiningdc1.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/joiningdc2.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/joiningdc3.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/joiningdc4.png" height="80%" width="80%">

<img src="https://github.com/maharjansabin12/screenshot/blob/main/joiningdc5.png" height="80%" width="80%">

<img src="" height="80%" width="80%">

<img src="" height="80%" width="80%">

<img src="" height="80%" width="80%">

<img src="" height="80%" width="80%">

<img src="" height="80%" width="80%">

<img src="" height="80%" width="80%">

