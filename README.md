# Offensive-Ethical-Hacking_101
# EH-using-GoBuster
<h1> This is an excersice and for ethical hackign trainign porposes only </h1>

 ### No bank accounts were hacked
 #### All images and copy rights are protected for TryHackMe

<h2>Description</h2>
Project: Hacking into a fakebank account to steal money using a virtual machine.
Objective: Transferring money from the fake bank account to the hacker account
Techniques used: command line to brute-force attack.
<br />


<h2>Tools/ Utilities Used</h2>

- <b>Virtual Machine</b> 
- <b>Firefox</b>
- <b>commandline</b>


<h2>Environments Used </h2>

- <b>Kali Linux</b> (21H2)

<h2>Attack walk-through:</h2>
We start with the hacker bank accoutn in negative 





![Kali linux negative account](https://github.com/TheRashaSharif/Offensive-Ethical-Hacking_101/assets/98124961/45aecdf3-f029-4808-a06a-dea7b88a0f25)


<p align="center">!


Launch the virtual machine: <br/>
Start the command line and type gobuster -u http://fakebank.com -w wordlist.txt dir  
 
  
  
  
  ![EH commandline](https://github.com/TheRashaSharif/Offensive-Ethical-Hacking_101/assets/98124961/adb5e584-f289-40ec-917d-30b19384a810)

 
  
<img src="C:![Uploading EH commandline.PNG…]()
\Users\User\Pictures\EH commandline.PNG" height="80%" width="80%" />
<br />
<br />
This command will find pages that exist on the site. it is /bank-transfer which allows to transfer between accounts
  You know it is the page indicated by status :200
  
 
<br />![Kali linix 2](https://github.com/TheRashaSharif/Offensive-Ethical-Hacking_101/assets/98124961/b8c09ef3-1eca-43ac-af01-eb5599707b33)

<br />
  
  When launching the page by adding bank-transfer to the fakebank.com URL an admin portal is open and for the project purpose we can transfer from bank account yo another. the results will be amaizing as the hacker negative account is positive again after the transfer!
  
  
  

<br />![Kali linux final hack](https://github.com/TheRashaSharif/Offensive-Ethical-Hacking_101/assets/98124961/912aeab9-f686-432c-b25a-62d01cafc31f)

<br />
Finally, this was an example to show how hackers can find vulnerability in a system and as a red team ethical hacker you can mock thier techniques.
  
  To learn cybersecurity from scratch, please visit:
 https://tryhackme.com/

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
