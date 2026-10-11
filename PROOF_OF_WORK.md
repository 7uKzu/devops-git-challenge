### **PROOF OF WORK**



###### **1. Git Commit History**



The following output shows the commit history of this repository:

**Output:**


\*   ba5e59f (HEAD -> main, origin/main) Merge pull request #1 from 7uKzu/development

|\\

| \*   c7bdda4 (origin/development, development) fix: resolved merge conflict

| |\\

| | \* c527d80 (origin/staging, staging) fix: staging label

| |/

|/|

| \* a0bb6de feat: updated script with staging env

|/

\* 0dc17f2 feat: initial commit with deploy script





###### **2. Reflection Questions**



**Q1. What is the difference between Git and GitHub?**

Git is a distributed version control system that tracks changes to files and records commits in a repository. 
It allows developers to create branches, compare changes, and manage project history locally. 
GitHub is an online platform that hosts Git repositories and provides collaboration features such as pull requests, code reviews, and issue tracking. 
Git can be used without GitHub, but GitHub uses Git to manage the repositories it hosts.



**Q2. Explain the three architecture stages: Working Directory, Staging Area, and Local Repository.**



The Working Directory is the folder where files are created, edited, and deleted. 
The Staging Area contains the changes selected for inclusion in the next commit, usually using `git add`. 
The Local Repository stores committed snapshots and the project's history. 
The normal workflow is to edit files, stage the desired changes, and commit them to the local repository.



**Q3. What is the difference between `git stash pop` and `git stash apply`?**



Both commands restore changes saved in the Git stash to the working directory. 
`git stash pop` restores the changes and normally removes the applied stash entry if the operation succeeds. 
`git stash apply` restores the changes but keeps the stash entry available for reuse. 
The stash entry is useful when the same saved changes may need to be applied again.



**Q4. What is the difference between `git fetch` and `git pull`?**



`git fetch` downloads new commits and reference updates from a remote repository without integrating them into the current branch. 
It lets developers inspect remote changes before deciding how to integrate them. `git pull` fetches remote updates and then integrates them into the current branch, normally by merging or, when configured, rebasing. 
Fetch is useful for inspecting updates first, while pull is used when you want to retrieve and integrate them.



