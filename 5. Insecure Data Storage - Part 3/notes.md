# 5. Insecure Data Storage - Part 3
![Image 1](6.1.png)
### Step 1: If we view the java code for this activity in jadx-gui, we'll notice that the data entries in the app are stored in the file 'uinfo'. 
![Image 1](6.3.png)
### Step 2: Enter a username and password in the app and press Save. 
![Image 2](6.2.png)
### Step 3: enter the root shell, and then navigate to the location of the file using 'cd /data/data/jakhar.aseem.diva'. Inside this directory you'll find the 'uinfo' file. View the contents of this file, and you'll see the contents of the file contains your inputted username and password in cleartext.
![Image 3](6.4.png)
