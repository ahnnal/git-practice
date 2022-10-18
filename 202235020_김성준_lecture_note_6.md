# Lecture 6 Git

##### Storing data

1. changes 
2. snapshots

---

and,,

1. local : checkout file and send the version 3 , 2 , 1 ..
2. centralized : Central VCS Serever send version database (version 3,2,1) to computer A,B
3. Distributed : Server computer send the Version database to intertwined coumpter with A,B

---
##### Three states in GIt

Modified , Staged and Comitted are in intersection

---

To use the Git , we have to setup Git first time

---

(*commands*)

- $ git init - initializing a repository in an Existing diretory
- $ git status - checking repository status
- $ git add [file_name] -adding a new file to be staged
- $ git add . - adding a new file to be staged
- $ git rm --cached [file_name] - unstaging a file
- $ nano .gitignore - ignoring a file
- $ git commit -m "commit message" - commit
