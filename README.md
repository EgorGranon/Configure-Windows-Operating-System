# Configure-Windows-Operating-System

<h2>Description</h2>
We will go through basic Windows OS configuration setups such as:<br />
<br />

- Encrypt a folder and its contents.

- Add a user to the list of those who can access an encrypted file.

- Enable Remote Desktop.

- Allow a user to connect to the computer using Remote Desktop.

- Allow Remote Assistance connections to this computer.

- Prevent certain applications from running at system startup.

- Share a folder and make it available for all users to read through a network connection.

- Increase security by implementing password requirements and account lockout policies.

- Force a user to change their password at the next logon.

- Restore a file to a specific version.

- Configure compatibility settings for an application.

<br />
<br />

<h2>1- Encrypt a folder and its contents</h2>
1)On your taskbar at the bottow of your screen select <b>File Explorer</b>
<br />
<br />
2)On the left of file explorer navigate to and expand <b>This PC</b> under which you will find all the disk volumes available on your PC. In this example we will select <b>D:</b>
<br />
<br />
Your screen should display all available files in the disk as follows:
<br />
<br />
<img src="https://imgur.com/u5GoHnP.png" height="65%" width="65%" alt="File Explorer"/>
<br />
<br />
3) Hover over the <b>Personnel</b> folder and <b>Right-Click</b>. Select <b>Properties</b>
<br />
<br />
4) In the General tab select <b>Advanced</b>.
<br />
<br />
Your screen should look similar to this:
<br />
<br />
<img src="https://imgur.com/RszT7N1.png" height="65%" width="65%" alt=""/>
<br />
<br />
5) Select <b>Encrypt contents to secure data</b> and then press <b>OK</b>
<br />
<br />
6) Select Apply in the Personal Properties window and make sure <b>Apply changes to this folder, subfolders and files</b> is selected and press <b>OK</b>.
<br />
<br />
<h2>2- Add a user to the list of those who can access an encrypted file</h2>
1) Hover over a desired encrypted file and <b>Right-click</b> before selecting <b>Properties</b>. In this example we will use a file named <b>Personnel Report.xlsx</b>.
<br />
<br />
Your screen should look similar as follows:
<br />
<br />
<img src="https://imgur.com/JV6GMav.png" height="65%" width="65%" alt=""/>
<br />
<br />
2) Next click <b>Advanced</b>  and in the Advanced Attributes tab click <b>Details</b>. You should be presented with the following screen:
<br />
<br />
<img src="https://imgur.com/5ZXR4pd.png" height="65%" width="65%" alt=""/>
<br />
<br />
3) Click <b>Add</b> and select the desired user you would like to add to the authorised list of users and click <b>Ok</b>.
<br />
<br />
<img src="https://imgur.com/GhWkzcR.png" height="65%" width="65%" alt=""/>
<br />
<br />
4) Finally proceed by selecting <b>Ok</b> to exit each tab and confirm your changes.
<br />
<br />
<h2>3- Enable Remote Desktop. </h2>
1)Right-click <b>Start</b> and got to <b>Settings</b>. On the default page <b>System</b> scroll down and click <b>Remote desktop</b> 
<br />
<br />
2)In Remote desktop click on the <b>Off</b> switch to turn Remove desktop access <b>On</b>. You should be prompted with a confirmation screen as follows:
<br />
<br />
<img src="https://imgur.com/9bEbQGE.png" height="65%" width="65%" alt=""/>
<br />
<br />
3) Select <b>Confirm</b> and Remote desktop will now be turned <b>On</b>
<br />
<br />
<h2>4- Allow a user to connect to the computer using Remote Desktop. </h2>
1) In Remote Desktop select <b>Remote Desktop users</b>
<br />
<br />
<img src="https://imgur.com/0jfQX2h.png" height="65%" width="65%" alt=""/>
<br />
<br />
2) Click <b>Add</b> and in the <b>Enter the object names to select</b> box type in the desired object/name of who you want to add
<br />
<br />
<img src="https://imgur.com/LzUXCwf.png" height="65%" width="65%" alt=""/>
<br />
<br />
3) Enter <b>Ok</b> to confirm changes.
<br />
<br />
<h2>5- Allow Remote Assistance connections to this computer. </h2>
1)To allow Remote Assistance to your computer in the Settings app navigate to and click <b>About</b> located at the bottow of <b>System</b>
<br />
<br />
<img src="https://imgur.com/RtnoFlC.png" height="65%" width="65%" alt=""/>
<br />
<br />
2)In the About menu under <b>Related Links</b> select any of the links. This will open <b>System Properties</b> and from there click on the <b>Remote</b> tab :
<br />
<br />
<img src="https://imgur.com/fMbYK2i.png" height="65%" width="65%" alt=""/>
<br />
<br />
3) In the <b>Remote</b> tab select <b>Allow Remote Assistance connections to this computer</b> and click <b>Ok</b>.
<br />
<br />
<h2>6- Prevent certain applications from running at system startup. </h2>
1) Go to <b>Task Manager</b> either by right-clicking on <b>Start</b> and selecting Task Manager or by pressing <b>Ctrl+shift+Esc</b> on your keyboard. Select the <Startup</b> tab as follows :
<br />
<br />
<img src="https://imgur.com/UONKbmM.png" height="65%" width="65%" alt=""/>
<br />
<br />
2) From here select the Applications you would like to disable and click <b>Disable</b> at the bottow right. Make sure you have disables the App by looking under <b>Status</b>.
<br />
<br />
<h2>7- Share a folder and make it available for all users to read through a network connection. </h2>
1) Open <b>File Explorer</b> from the taskbar.
<br />
<br />
2) In File Explorer navigate to <b>This PC</b> and locate a folder you would like to share in one of your available drives. In this example I will use the Software folder in the <b>Data (D:)</b> drive.
<br />
<br />
<img src="https://imgur.com/d0ufdVn.png" height="65%" width="65%" alt=""/>
<br />
<br />
3) Right-click your folder and enter Properties from which you will go to the Sharing tab as follows:
<br />
<br />
<img src="https://imgur.com/jsrQ2bl.png" height="65%" width="65%" alt=""/>
<br />
<br />
4) Now select <b>Share</b> inside which you will select <b>Everyone</b> from the drop down menu next to Add and click <b>Add</b>
<br />
<br />
<img src="https://imgur.com/NjQc7SD.png" height="65%" width="65%" alt=""/>
<br />
<br />
5) Under Administrators you should now see <b>Everyone</b> and you can customize the Permission Level on the right.
6) Now select <b>Share</b> and then <b>Done</b>.
<br />
<br />
<h2>8- Increase security by implementing password requirements and account lockout policies. </h2>
1)Search for <b>Local Security Policy</b> in the search field</b>
<br />
<br />
2)In the Local Security Policy window expand <b>Account Policies</b> and then <b>Password Policy.</b> As follows:
<br />
<br />
<img src="https://imgur.com/KULZBX2.png" height="65%" width="65%" alt=""/>
<br />
<br />
3)Double-Click <b>Minimum Password Length</b> and set to desired length. In this example we will pick 10 and press <b>Ok</b>
<br />
<br />
<img src="https://imgur.com/xhKbZ8q.png" height="65%" width="65%" alt=""/>
<br />
<br />
4) Double-Click <b>Password must meet complexity requirements</b> and choose <b>Enable</b>
<br />
<br />
<img src="https://imgur.com/Q9RKnJ4.png" height="65%" width="65%" alt=""/>
<br />
<br />
5)Under Password Policy select <b>Account Lockout Policy</b>. Double-click <b>Account lockout threshold</b> and select the desired amount of failed attempts you would like to allow before activating the lockout.
<br />
<br />
<img src="https://imgur.com/gXJcAdu.png" height="65%" width="65%" alt=""/>
<br />
<br />
6) Select <b>Ok</b> and accept suggested value changes for duration and counter.
<br />
<br />
<h2>8- Force a user to change their password at the next logon. </h2>
1)Select <b>Computer Management</b> by right-clicking start.
<br />
<br />
2) Expand <b>Local Users and Groups.</b> and select <b>Users</b>
<br />
<br />
<img src="https://imgur.com/PC4ESZb.png" height="65%" width="65%" alt=""/>
<br />
<br />
3) Select the user you would like to apply the policy to by right clicking over them and selecting <b>Properties</b> (In this example we pick the user Ethan)
<br />
<br />
4) Check the box for <b>User must change password at next logon</b>
<br />
<br />
<img src="https://imgur.com/O9qPv6M.png" height="65%" width="65%" alt=""/>
<br />
<br />
5) Select <b>Ok</b> and close Computer Management.
<br />
<br />
<h2>10- Restore a file to a specific version. </h2>
1)Open <b>File Explorer</b> from the task bar
<br />
<br />
2)Select a file you would like to restore in a folder. In this example we will pick the Executive Brief.pptx in the presentations folder.
<br />
<br />
3) Right click the file, select <b>Show more options.</b> and then select <b>Restore previous versions.</b>
<br />
<br />
<img src="https://imgur.com/r0k9fI6.png" height="65%" width="65%" alt=""/>
<br />
<br />
4)Select the desired version you would like to go back to and select <b>Restore</b> and <b>Replace the file in the destination</b>
<br />
<br />
<h2>11- Configure compatibility settings for an application. </h2>
1) To run a file in compatibilty mode right click on an executable file (.exe) and go into <b>Properties</b>
<br />
<br />
2) Go into the compatibility tab and select <b>Run this program in compatibility mode for</b>
<br />
<br />
<img src="https://imgur.com/effp7lX.png" height="65%" width="65%" alt=""/>
<br />
<br />
3) Select the version of windows you would like to run with the program.
4) Add any extra boxes in settings such as <b>Run this program as an administrator</b>
5) Select <b>OK</b>
