<h1>File Integrity Monitor</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This Project constists of creating a File Integrity Monitor (FIM) system that constantly loops seeing if the hashs of the text files change and then alerting the user.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Open up PowerShell and start writing the necessary script: <br/>
<img src="https://imgur.com/kG8soAm.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
What code looks like once it is finished and working:  <br/>
<img src="https://imgur.com/OLVlVz6.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Script assigns hashes to each text file giving it a virtual thumbprint which will allow us to verify if anything has changed: <br/>
<img src="https://imgur.com/hhzUUpF.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Enter A to create a baseline.txt file inside the folder:  <br/>
<img src="https://imgur.com/0UkHbP1.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
What folder looks like after code runs and baseline.txt is created:  <br/>
<img src="https://imgur.com/ZtxH1rI.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
If we add a new file to the folder the program alerts us:  <br/>
<img src="https://imgur.com/W2OBXOY.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
If someone tries altering the info inside the .txt file the hash assigned to it changes, once again alerting the user:  <br/>
<img src="https://imgur.com/QYCePE2.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Deleting a file also alerts the user: <br/>
<img src="https://imgur.com/pA7xzqX.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
