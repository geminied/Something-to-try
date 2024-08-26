# Something-to-try
First try
<br>
I want to know how to use git and git hub

copying or cloning into local machine: git clone <-https link from repository code->

showing the version: git --version 

to clear terminal: clear

change directory (folder) : cd <-folder name-> (forward moving)

backward moving: cd ..

list files : ls or dir

hidden files: ls -h or dir -h

check file status: git status

add new or modified file: git add <-file name-> 

add all new or modified files: git add . 

to commit: git commit -m "message"

making new directory or sub repository: mkdir ,-new repository name->

push command; git push origin (original file) main (branch)

making new repository git repository: git init

to connect new repository: git remote add origin <-new repo link->

to verify remote: git remote -v

to check branch: git branch

to rename branch: git branch -M main (new branch name)

to always push in the same branch(to set upstream): git push -u origin main

after that you can use git push and it'll push to the main branch

to delete branch: git branch -d <-branch name->

to navigate: git checkout <-branch name->

to create new branch: git checkout -b <-new branch name-> (but can't delete the branch you are currently on)

merging code:

way 1:

to compare commits, branches, files and more: git diff <-branch name->

to merge branches: git merege <-branch name-> (this merges the current branch with <-branch name->)

Way 2:
pull Request (pr): 

to fetch and download content (to get changes in local file): git pull origin main
