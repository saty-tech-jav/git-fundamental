# Fundamentals of Github and git NOTES
## GIT:

Version control system is a tools that helps to track change in code.

1.It helps to track the history
<br>
2.Collaborate with peers

## GITHUB:

Website that allows developers to store and manage their code using git.

folder==repository

README.md file is the basic file structure

2 step generally involved

1.add
<br>
2.commit

## COMMANDS

1.git --version
<br>
2.git add .(For adding modified files and all newly added files)
<br>
3.git add <filename> (for specific file name)
<br>
4.git commit -m "adding first change"
<br>

## CONFIGURATION OF GIT

5.git config --global user.name "satyamkumar"
<br>
6.git config --global user.email "sat133kumar@gmail.com"
<br>
7.git config --list
<br>

remote is called=git hub repo
<br>
local is called=laptop/pc
<br>

8.ls -a (command used for watching hidden files)
<br>
9.ls (to see all the files)
<br>
10. cd d: (to change directory)
<br>
11. cd .. (To come out from directory)
<br>
12.mkdir (Create new directory)
<br>
13.git status (For checking the status)
<br>
14.git clone (For clonning the project)
<br>

Change==modified
<br>
new file=untracked
<br>
add=staged (add new or changed files in your working directory to the git staging area)
<br>
commit=unchanged (it is the record of change)
<br>

15.git push origin main (for pushing code in repo/remote from local)
<br>

## BRANCHES

16.git branch (to check branch)
<br>
17.git branch -M main(to rename branch)
<br>
18.git checkout <branch name>  -- (for switching to that given branch name)
<br>
19.git checkout -b <branch-name> --(for creating new branch)
<br>
20.git branch  -d <branch-name> --(to delete branch)
<br>

## MERGING CODE

21.git diff <branch name>  --comparision will made to <branch-name> by switched branch name
<br>
22.git merge <branch name>
<br> 
23.Merging of branch can be done by creating PR(Pull request)
<br>

## GIT CONFLICT

An event that takes place when git is unable to automatically resolve difference in code 
between branches.

## RENAMING OF BRANCH ON GITHUB ALSO

24.git push origin :old-name-of-branch-on-github
<br>
25.git branch -m old-name-of-branch-on-github new-name-for-branch-you-want
<br>
26.git push origin new-name-for-branch-you-want
<br>

## CREATION OF REPO FROM COMMAND LINE 

27.echo "# EX" >> README.md
<br>
28.git init
<br>
29.git add README.md
<br>
30.git commit -m "first commit"
<br>
31.git branch -M main
<br>
32.git remote add origin https://github.com/saty-tech-jav/EX.git
<br>
33.git push -u origin main
<br>




 ## PUSH EXISTING REPO FROM COMMAND LINE


34.git remote add origin https://github.com/saty-tech-jav/EX.git
<br>
35.git branch -M main
<br>
36.git push -u origin main
<br>




