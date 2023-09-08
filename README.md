# File_permissions_in_Linux

<h1>Lab 3</h1>

<h2>Description</h2>
In this lab, I am learning how to examine and manage file permissions. These skills can be used when configuring user authorization. I am using Linux commands in the Bash shell to complete this lab. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash shell</b> 
- <b>Bash</b>

<h2>Environments Used </h2>

- <b>Qwiklabs (Provided by Coursera [Google Cybersecurity course])</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch and Start : <br/>
<img src="https://imgur.com/dr3X6nt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/V7y2XId.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check permissions for files in a directory<br>1. Navigate to the projects directory.<br>2. List the contents and permissions of the projects directory.<br>3. Check whether any hidden files exist in the projects directory.<br>
  <br/>
<img src="https://imgur.com/9u5k3DD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check for incorrect file permissions and change permissions as needed<br>
  1. Check whether any files in the projects directory have write permissions for the owner type of other.<br>
  2. Change the permissions of the "project_k.txt" file so that the owner type of other doesn’t have write permissions<br>
  3. List the contents and permissions of the current directory and check if the group has read or write permissions.<br>
  4. Change permissions of the "project_m.txt" file so that the group doesn’t have read or write permissions.<br>
  5. Check the permissions of the hidden file .project_x.txt<br>
  6. Change the permissions of the file .project_x.txt so that both the user and the group can read, but not write to, the file.
  <br/>
<img src="https://imgur.com/2bByk2d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remove unauthorized access to a directory<br>
  1. Check the permissions of the drafts directory.<br>
  2. Remove the execute permission for the group from the drafts directory.<br>
  <br/>
<img src="https://imgur.com/iAT6pwf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
