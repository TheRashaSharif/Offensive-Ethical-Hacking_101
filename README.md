# Offensive-Ethical-Hacking_101
# EH-using-GoBuster
<h1> This is an exercise and for ethical hacking training purposes only </h1>

 ### No bank accounts were hacked
 #### All images and copyrights are protected for TryHackMe

<h2>Description</h2>
Project: Hacking into a fake bank account to steal money using a virtual machine.
Objective: Transferring money from the fake bank account to the hacker account
Techniques used: command line to a brute-force attack.
<br />


<h2>Tools/ Utilities Used</h2>

- <b>Virtual Machine</b> 
- <b>Firefox</b>
- <b>commandline</b>


<h2>Environments Used </h2>

- <b>Kali Linux</b> (21H2)

<h2>Attack walk-through:</h2>
We start with the hacker bank account in negative 



![Kali linux negative account](https://github.com/TheRashaSharif/Offensive-Ethical-Hacking_101/assets/98124961/1c5a8c26-eb2d-4e83-b96e-7e8025c0dd18)


<p align="center">!


Launch the virtual machine: <br/>
Start the command line and type gobuster -u http://fakebank.com -w wordlist.txt dir  
 
  
  
  ![EH commandline](https://github.com/TheRashaSharif/Offensive-Ethical-Hacking_101/assets/98124961/c4ca5ee4-f390-4642-8e5d-39e3ffc497bb)

  
<br />
This command will find pages that exist on the site. it is /bank-transfer that allows to transfer between accounts
  You know it is the page indicated by status :200
  
 

  ![Kali linix 2](https://github.com/TheRashaSharif/Offensive-Ethical-Hacking_101/assets/98124961/d64830f9-9e88-47ed-bd2e-c5bfd67ab9aa)

  When launching the page by adding bank-transfer to the fakebank.com URL an admin portal is open and for the project purpose, we can transfer from one bank account to another. The results will be amazing as the hacker's negative account is positive again after the transfer!
  
  
  

![Kali linux final hack](https://github.com/TheRashaSharif/Offensive-Ethical-Hacking_101/assets/98124961/9520f114-bd0b-45a4-8670-e911b940d56a)


Finally, this was an example to show how hackers can find vulnerabilities in a system, and as a red team ethical hacker, you can mock their techniques.
 
  
To learn cybersecurity and more please visit:
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
