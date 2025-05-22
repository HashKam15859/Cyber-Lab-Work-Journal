# 7. Input Validation Issues - Part 1
![Image 1](8.1.png)
### Step 1: First simply attempt to search for a random user. You'll get a 'User: (randomuser) not found' prompt. This shows that if the condition is true, then the prompt will display all the details. 
![Image 2](8.2.png)
### Step 2: If we view the underlying code of the activity, we'll observe that its vulnerable to SQL Injection. 
![Image 3](8.4.png)
### Step 2: We now attempt to do an SQL Injection attack, and input injected code " 'OR'1'='1'-- " into the field. This injection successes, and a prompt appears with all the user details. 
![Image 4](8.3.png)
