# 4. Insecure Data Storage - Part 2
![Image 1](5.1.png)
### Step 1: If we view the code of this activity in jadx-gui, you'll notice that the we can see the database file that's beign created to store the inputted usernames and password. 
![Image 2](5.4.png)
### Step 2: Input any username and password into the provided fields in the app and submit. 
![Image 3](5.5.png)
### Step 3: Open the root shell through powershell, and browse through the directories to find the 'ids2' file. Remember the path and pull the file from the device emulator to the current device's storage using the command 'adb pull /data/data/jakhar.aseem.diva/databases/ids2'. 
![Image 4](5.3.png)
### Step 4: Drag and drop the file SQLite Viewer (found onling). Then select the command to view the contents of 'myuser' and execute the presented command. You'll be able to the view your previously inputted username and password in the result. 
![Image 5](5.2.png)
