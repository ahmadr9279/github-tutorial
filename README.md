![alt text](https://c1.staticflickr.com/6/5622/22160892602_e5474a698d.jpg)
# GitHub Tutorial

_by Ahmad Rabah_

---
## Git vs. GitHub
__Git__ is an application that can be downloaded to your computer which is called your __local machine__. Git is used to take snapshots of __files__ and keeps track of different versions of them. You can add, delete, move, and change them (among other things). __Github__ serves a similar purpose, except it is used by multiple people __collaborating__ with each other on the __same project__. While Github requires Git, Git doesn't require Github to be used. Because Github is used on the internet and is where you save your files on the cloud, it can be called the __remote server__. 


---
## Initial Setup
If you want to begin learning how to use Github and Git follow these 3 simple steps:
1. Create a [C9](https://c9.io) account or download [Git](https://git-scm.com) on your computer. This will be where all your local changes will be located in. In order to be able to use Github, you need to have Git. C9 can be a replacement if you don't want to download Git and does the same thing as it too. 
2. Create a [Github](https://github.com) account. This is where all your remote repositories will be located in. If you decided to create a C9 account, you can link it with Github. This means that you can log in C9 with your Github username and password.
3. SSH key Used to connect repos
---
## Repository Setup
In order to make a repository, follow these steps below:  
#### 1. `mkdir folder name`
Before starting to write text or creating files, you need a folder. This command creates a folder and you use it by typing `mkdir-name-you-want-for-your-folder`.
#### 2. `git init`
This command allows the directory that you are in to be changed. So this is very important. Just type `git init` to initialize your project.  
#### 3. `touch file name`
To write text, you need to make a file. To make a file, you need to be in a folder. After you are in a folder , type `touch file_name` to make a file.
#### 4. `git add`
After writing text in the file, you type `git add file_name` to stage the changes.
####  5. `git commit -m " "`
This command is used to save all the changes/modifications you have made. You also have to write a message in the present tense explaining what was done.  

#### 6. `git remote add origin url`  
To connect your local repo to your remote repo, do: `git remote add origin url`. You can obtain the url by going to the repository you want to connect your local repository to in your github account.


---
## Workflow & Commands
In this section it will be explained to you which commands should be constantly used.

`git status`  
You use `git status` in order to check if your project is staged. You use this by typing `git status`.

`git add`  
Once you have written text and you want to stage the changes, you would use the command `git add`. In order to use git add you would type `git add file-name-you-made-changes-to`. 

`git commit`  
After you are done making all changes to your files/directories, you should take a "snapshot" of them. What this means is that when you do git commit, you can later view all your changes you have just recently made. While viewing those modifications, you will also see a message with them with which you have created. When you use git commit, you also add a meassage in the present tense describing what you did. To use `git commit`, do: `git commit -m "insert message here"`.

`git push`  
If you want to transfer commits from your local repository to your remote repository, you would use `git push`. This command takes the latest changes you have made to your local repo and takes it to your remote repo.




---
## Rolling Back Changes
Sometimes you might make a __mistake__ while on the __command line__. You might've accidently __changed__ something, and now you want to __undo it__. Well.. You have come to the right place! Here, it will be explained how to __undo__ some of the __most common commands__.
### How to Undo a(n): 
* #### edit  
`git checkout -- filename`.
* ### `add`  
In order to undo an `add` use the command `git reset HEAD filename`. This will remove the last add you have made.
* ### `commit` 
When you `commit` something and you want to undo this action, use the command 
* ### `push`  
* In order to undo `git push` do `git revert fill-in` where fill in represents the last commit you made.

git revert a867b4af b5eee4ca c766c053
Where a… is the most recent commit
Where b… is the commit before that
Where c… is the 3rd-most recent commit
NOTE: you can also do these one at a time

## Collaboration
  so.   
fork & clone, pull requests and pull






