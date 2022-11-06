# super-duper-dollop
we use super-duper-dollop project for GitHub &amp; Git practice

1) What is Git & Github
2) Why do we need Git
3) How to initilize a git repo ( git init)
4) How to move files from working area to staging area ( git add filename1 filename2 or git add .)
5) How to commit  (git commit -m "Commit Message")
6) How to clone a remote repository. git clone remote_repo URL
7) How to remove unwanted files from working directory  ( git rm --cached filename)
8) How to unstage a staged ( git restore)
9) How to set user properies
10) Howv to clone a Git repository from github
11) How to check all the branches do we have
12) What is git rm & git restore
13) what is git log
14) What is git branching 
15) How to create a branch
16) How to switch to a new branch
17) How to remove branches and branch names
18) How to push local changes from staging area to remote repository
19) How to pull changes from remote repository (github)
20) What is README.md
21) what is .gitignore file
22) Who are collaborators & How to add collaborators in your project
22) How to protect branches in github & why should we protect branches
23) create a merge request
24) github insights
25) Forking --> how is it useful
26) What is merge conflict & how to resolve it
27) what is git diff in working directory  & staged area (--staged)
        git diff HEAD <file_name>
        git diff <file_name>
        git diff --staged <file_name> or  git diff --cached <file_name>,
        git diff <branch_name1> <branch_name2> <file_name>
        git diff <commit_hash> <commit_hash> 

28) git reset
29) git stash --> Stash is to store the uncompleted work in a particular area which you will use in future
30) git revert -->  In Git, the term revert is used to revert some changes. The git revert command is used to apply revert operation. It is an undo type command. However, it is not a traditional undo alternative. It does not delete any data in this process; instead, it will create a new change with the opposite effect and thereby undo the specified commit
31) git reset --> The term reset stands for undoing changes. The git reset command is used to reset the changes.









1) What is branch
2) Why are brnaches are required
3) How branches works
4) Pracitce around branches
creating new unique branch
switch to new branch

==================
===================



* What is Version control System?

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later

* What is Git ?
Git is a linear version control system which can be used to maintain & track the history of your files over a period of time.

* The Three States of Git
Pay attention now — here is the main thing to remember about Git if you want the rest of your learning process to go smoothly. Git has three main states that your files can reside in: modified, staged, and committed:

Modified means that you have changed the file but have not committed it to your database yet.

Staged means that you have marked a modified file in its current version to go into your next commit snapshot.

Committed means that the data is safely stored in your local database.

This leads us to the three main sections of a Git project: the working tree, the staging area, and the Git directory.

![image](https://user-images.githubusercontent.com/117242284/200162445-669e0e43-4a6c-40b0-8e78-9d6217d0aaa4.png)


**The working tree** is a single checkout of one version of the project.

**The staging area** is a file, generally contained in your Git directory, that stores information about what will go into your next commit. Its technical name in Git parlance is the “index”, but the phrase “staging area” works just as well.

**The Git directory** is where Git stores the metadata and object database for your project. This is the most important part of Git, and it is what is copied when you clone a repository from another computer.

The basic Git workflow goes something like this:

        1.You modify files in your working tree.

        2.You selectively stage just those changes you want to be part of your next commit, which adds only those changes to the staging area.

        3.You do a commit, which takes the files as they are in the staging area and stores that snapshot permanently to your Git directory.
        
 
 Setting your username & email in Git
 ![image](https://user-images.githubusercontent.com/117242284/200162799-59bb03b3-601f-4ff5-9783-c7a5cc083ba5.png)
![image](https://user-images.githubusercontent.com/117242284/200162831-9e51bbb6-b121-4456-8496-d6742489e0db.png)


**Initializing a Repository in an Existing Directory**
        If you have a project directory that is currently not under version control and you want to start controlling it with Git, you first need to go to that project’s directory and then apply the command **git init** from command prompt.
        ![image](https://user-images.githubusercontent.com/117242284/200162957-d352aa6d-9020-46e2-8c67-110ca5166cb4.png)

**Clonining a remote repository**
        If you want to get a copy of an existing Github/Gitlab repository then we should follow the below process
        Open command prompt and copy HTTP version of github URL and then apply git clone https://github.com/Kamesh591/super-duper-dollop.git 
        ![image](https://user-images.githubusercontent.com/117242284/200163370-2d5e25e8-698c-4222-b112-2ae6fe36d466.png)


        

