<h1>Detecting Rootkits</h1>


<h2>Description</h2>
In this lab, I learned how to detect rootkits threat. Rootkits provide another threat to data in use. Rootkits, which operate at the operating system level, can intercept data from terminals, network connections, and the keyboard, and may facilitate the installation of system-level software processes, hidden files and user accounts.
<br />



<h2>Environments Used </h2>

- <b>Kali GNU/Linux Rolling</b> 

<h2>Utilities and Language </h2>

- <b>Terminal</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar, click Terminal: <br/>
<img src="https://i.postimg.cc/GmVSSqbx/Screen-Shot-2022-09-17-at-5-16-00-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
<br />
In the terminal window type the following commands to detect rootkits:  <br/>
1. dpkg -l | grep chkrootkit <br/>
2. locate chkrootkit <br/>
3. echo $PATH <br/>
4. chkrootkit <br/>
<img src="https://i.postimg.cc/tRfbHtR7/Screen-Shot-2022-09-17-at-5-21-26-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  


  
   
  

  
