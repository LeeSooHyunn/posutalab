# Week 5 Lecture notes
---
 **1. I/O Redirection :**   
- Standard Output:     
\-default : screen .   
\-you can redirect output using ">" after a command to create and save the output in a file   
\-use ">>" appends output to an extising file or create and write to a new file      

- *Standard Input*:        
\-default : keyboard   
\-you can redirect input from a file using "<"   
---
 **2. Pipelines "|":**   
\- pipeline feeds output of previous command to input of next command
\- press "q" key to exit the screen   

---
**3. Expansion:**   
\- Special characters expand its meaning when given to shell commands   
ex) $ echo * : prints files in the current directory.   
ex) $ echo ~ : prints the current user's directory.   


***Tip:Backslash***   
: backslash can be used to ignore line change in command, to enter a long command in multiple lines.   

---
**4. Permissions**   
\- Linux is a multi-user system.
\- Files & directories have a permission assigned differently to owner / group / others.   


- Changing Permissions:   
\-"chmod" changes permissions   
rwx = 111 in binary = 7   
rw- = 110 in binary = 6   
r-w = 101 in binary = 5
r-- = 100 in binary = 4

---
**5. Superuser**    
\- A superuser has all system administation authority   
\- Put "Sudo" before the command if you are a superuser   

---
**6. Text Editors**   
\-vi, vim   
\-Emacs   
\-nano   
\-gedit   
\-kwrite   


