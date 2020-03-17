## Notes

Version Control is a system that allows you to revisit various versions of a file. 
Local version control systems were stored on hard disk
Centralized Version control systems(CVCS) was using servers to store changes
Distributed Version Control systems(DVCS) was a step up from CVCS which allowed clients to create mirrored repositories. 

Git is a DVCS that stores snapshots of your files. A commit is a changed version. 

Files in get can reside in three main states: 
committed - data is stored in a local database
modified - file has been changed but not commited to database
staged - flagged a file's changed version to be commited in the next snapshot

git status
git add Readme
git status
git commit -m
git status
git push origin master
git status

anytime we make change

git status
git add Readme.md
git status
git commit -m "include a message" 
git status
git push origin master


- fixing conflicts
git pull origin master

choose on vs code
git status
git commit -m "fix 
git status
git commit - m
git status
git push origin master

ACP add commit push

deployment

# Setup up a git Repository

## Importing

cd test  
git init  
git add *.c
git add LICENSE
git commit -m “any message here”

## Cloning

git clone (enter repository http url)

## Workflow

The local Git repository has three components:

1. Working Directory: The actual files reside here.
1. Index: The area used for staging
1. Head: Points to the most recent commit

working directory > add > index > commit > head

![local repository structure](https://www.udemy.com/blog/wp-content/uploads/2015/08/image036.png)

The life cylce of File Status
![The life cycle of File Status](https://www.udemy.com/blog/wp-content/uploads/2015/08/image006.png)






