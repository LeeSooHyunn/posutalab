# 6Week Lecture Notes   
Git-1
---
- Version Control and Collaboration:   
changes: storing data as changes to the base version   
snapshots: storing data as sanpshots ( Git)   
- Three staes in Git:   
\-Working Directory
\-Staging Area
\-git directory
---
- Git config: First-time setup   
1) System level: --system option. Affects all uses and repositories on the system (administrative)   
2) Global (user) level: --global option. Affects all repositories of a current user   
3) Local level: --local option. Specific to the current repository   

- Initializing a Repository in an Existing Directory : $ git init   
- Checking Repository Status : $ git status    
- Adding a new file to be staged (tracked) : $ git add [file_name]   
- Adding all files to be staged (tracked) : $ git add .
- Unstaging a file :$ git rm –cached [file_name]
- Ignoring a file
\- ignore all .a files : *.a
\- but do track lib.a, even though you're ignoring .a files aboave  !lib.a
\- only ignore the TODO file  in the current directory, not subdir/ TODO/TODO   
- Commit : $ git commit -m “commit message”
  
