<h1>Creating and Managing Directory and Files in Linux</h1>

<h2>Description</h2>
In this project, we will be using Linux commands to create and modify a directory and files within it.<br/> 

<br/>

<h2>Project</h2>

<p align="left">
  <b>1. </b>First things first - We need to verify the current directory, this is crucial so we know how to navigate! <br/>
  <br/>
<img src="https://i.imgur.com/nDczWZB.png" height="80%" width="80%" alt="pwd"/>
<br/>
<br/>
<br/>
<b>2. </b>Now, let's say our boss tells us to add a 'log' directory. Let's verify that we don't already have a 'log' directory by running a command to check... <br/>
  <br/>
    <img src="https://i.imgur.com/ECyaNey.png" height="80%" width="80%" alt="Current Directory"/>
<br/>
<br/>
<br/>
<b>3. </b>Alright, perfect. No 'log' directory, so let's create one! <br/>
  <br/>
    <img src="https://i.imgur.com/sV3CIrs.png" height="80%" width="80%" alt="Creating a log directory"/><br/>
     <p>Note:<br/>Make sure to verify the directory has been added by running 'ls'<br/>
  <br/> 
  <br/>
<b>4. </b>Now, let's remove the 'temp' directory.<br/>
 <br/>
    <img src="https://i.imgur.com/hvbXg1I.png" height="80%" width="80%" alt="Removing a directory"/><br/>
       <p>Note:<br/>Make sure to verify the directory has been removed successfully by running 'ls'. We can see that 'temp' is no longer listed as well.<br/>
<br/>
<br/>
<b>5. </b>Perfect! Now, let's go into 'notes' directory and see if we have a file we can move.<br/>
 <br/>
    <img src="https://i.imgur.com/5Yl0Tu9.png" height="80%" width="80%" alt="Navigate to notes"/><br/>
         <br/>
    Now we see that in 'notes' we have two files, a 'Q3patches.txt' file and a 'tempnotes.txt' file.<br/>
<br/>
<br/>
  <b>6. </b>Let's move 'Q3patches.txt' file from this 'notes' directory, over to the 'reports' directory.<br/>
    <img src="https://i.imgur.com/SoHW051.png" height="80%" width="80%" alt="Moving file to new directory"/><br/>
<br/>
<br/>
We were able to move the file by the <i>'mv' command</i><br/>
Also, we checked that in the 'reports' directory, that the 'Q3patches.txt' file has been moved successfully!<br/>
<br/>
<br/>
  <b>7. </b>Now, let's get rid of that lone 'tempnotes.txt' file in the 'notes' directory.<br/>
    <img src="https://i.imgur.com/O5KMb4d.png" height="80%" width="80%" alt="Deleting file"/><br/>
<br/>
<br/>
We now see that 'ls' in the 'notes' directory, contains no more 'tempnotes.txt' file!<br/>
<br/>
<br/>
  <b>8. </b>Our 'notes' directory is now empty, so let's create a new file called 'tasks.txt'.<br/>
    <img src="https://i.imgur.com/t5NNXDP.png" height="80%" width="80%" alt="Creating a new file"/><br/>
<br/>
<br/>
We can create new files with the 'touch' command. Also, now we see that within the 'notes' directory, a new file called 'tasks.txt' is now present!<br/>
<br/>
<br/>
  <b>9. </b>Now, let's edit that new file with some text - 'Completed Tasks 1. Managed file structure in home/analyst'.<br/>
    <img src="https://i.imgur.com/3t6KV1z.png" height="80%" width="80%" alt="Creating a new file"/><br/>
<br/>
Note:<br/>Use 'Control+X' to Exit, which will prompt you to save by pressing 'Y' or 'N'.<br/>
Once you have pressed - 'Y' or 'N', finish that command to save, or not, by pressing 'enter'.<br/>
<img src="https://i.imgur.com/uxcerWX.png" height="80%" width="80%" alt="Save Y or N"/><br/>
<br/>      
Note:<br/>The recommended sequence of commands for saving a file with the nano text editor is to use 'Control+O' to tell nano to save the file and then use 'Control+X' to exit immediately.<br/>
<br/>
<br/>
  <b>10. </b>Lastly, let's see if what we have entered into the 'tasks.txt' file is in there.<br/>
    <img src="https://i.imgur.com/m9RpTM0.png" height="80%" width="80%" alt="Concatenate tasks"/><br/>
<br/>
<br/>
Nice! Once we've 'cat' or 'concatenate', to see the contents of 'tasks.txt' we can see that our text has been saved within that 'tasks.txt' file! This is one of my project portofolio on how to manage files within Linux!<br/>
<br/>
<br/>
         
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
