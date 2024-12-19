#README.MD

#README IS A MARKDOWN FILE
.MD EXTENSION IS USED FOR MARKDOWN FILES

#1 - create and initialize a new git repository, add file, commit
#mkdir [directory_name]
#cd [directory_name]
#git init
#touch [README.MD]
#git add [README.MD]
#git commit -m "MESSAGE"

...

#2 - create a new branch
#git checkout -b [branch_1] - creates and switches to the new branch

or

#git branch [branch_2] - creates a new branch
#git checkout [branch_2] - switches to the new branch

to get back to main branch use: git checkout main

#cant push a branch to a remote repository if it doesnt exist on the remote repository
#to push a branch to a remote repository use: git remote add origin [url] - from the remote repository in github

-create one with the same name
choose/copy ...or push an existing repo from the command line

this will push the branch to the remote repository

- find a visual git tool to help you understand the git tree - not understand branches

git fork - is when you copy a repository from one account to another account
git clone - is when you copy a repository from one account to your local machine

Git has rules that it uses to determine what the code should look like after the merge. However, there are some instances where git can’t automatically figure this out using its rules, so it needs you to manually tell it what the code should look like after the merge. This is called a Merge Conflict. 

looks like: 

<<<<<<<< branch_name
 # Code from the branch_name Branch
========
# Code from the main Branch
>>>>>>>> main


