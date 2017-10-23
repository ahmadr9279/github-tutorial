![alt text](https://assets-cdn.github.com/images/modules/open_graph/github-mark.png)
# GitHub Tutorial

_by Ahmad Rabah_

---
## Git vs. GitHub
__Git__ is an application that can be downloaded to your computer which is called your __local machine__. Git is used to make __changes__ to your own __files/folders__. You can add, delete, move, and change them (among other things). __Github__ serves a similar purpose, except it is used by multiple people __collaborating__ with each other on the __same project__. While Github requires Git, Git doesn't require Github to be used. Because Github is used on the internet and is where you save your files on the cloud, it can be called the __remote server__. 


---
## Initial Setup
If you want to begin learning how to use github and git follow these 3 simple steps.
1. Create a c9 (link) account or download git (link) on your computer. This will be where all your local changes will be located in.In order to be able to use github, you need to have git. c9 can be a replacement if you don't want to download git and does the same thing as it too. 
2. Create a github(link) account. This is where all your remote repositories will be located in. If you decided to create a c9 account, you can link it with github. This means that you can log in c9 with your github username and password.
3.  SSH key Used to connect repos
---
## Repository Setup
#### `init`  
#### `add` & `commit`  
#### New repo on github   
#### `remote`
In ordwr to make a repository, follow these steps below. 
1. "Mkdir folder name".
Before starting to write text or creating files, you need a folder. This command creates a folder and you use it by typing "mkdir name you want for your folder".
2. "Git init".
This command allows the directory that you are in to be changed. So this is very important. Just type "git init" to initialize your project.
3. "Touch file name".
To write text, you need to make a file. To make a file, you need to be in a folder. After that, type "touch file name" to make a file.
4. "Git add". After writing text in the file, you type "git add file name" to save those changes.
5.  "Git commit -m""". This command is used to save all the changes/modifications you have made. You also have to write a message in the present tense explaining what was done. 
6. To connect your local repo to your remote repo, do: git remote add origin url". You can obtain the url by going to the repository you wnt to connect your local repository to in your github account.


---
## Workflow & Commands
In this section it will be explained to you which commands that should be constantly used.
Git status
You use "git status" in order to check if your project is initializef and is ready to be made changes on. You use this by typing "git status".

Git add
Once you have written text and you want to save the changes, you would use the command "git add". In order to use git add you would type "git add file name you made changes to".italicize part

Git commit
After you are done making all changes to your files/directories, you should take a "snapshot" of them. What this means is that when you do git commit, you can later view all your changes you have just recently made. While viewing those modifications, you will also see a message with them with which you have created. When you use git commit, you also add a meassage in the present tense describing what you did. To use git commit, do: git commit -m"insert maessage here".

Git push
If you want to transfer major changes from your local repository to your remote repository, you would use "git push." This command takes the latest changesbyou have made to your local repo and takes it to your rrmote repo.




---
## Rolling Back Changes
Sometimes you might make a __mistake__ while on the __command line__. You might've accidently __changed__ something, and now you want to __undo it__. Well.. You have come to the right place! Here, it will be explained how to __undo__ some of the __most common commands__.
### How to Undo: 
#### * edit  
git checkout -- filename
#### * `add`  
In order to undo an `add` use the command `git reset HEAD filename`. This will remove the last add you have made.
#### * `commit` 
When you `commit` something and you want to undo this action, use the command 
#### * `push`  




If you want to begin learning how to use github and git follow these 3 simple steps.
1. Create a [c9](link) account or download [git](link) on your computer. This will be where all your local changes will be located in.In order to be able to use github, you need to have git. c9 can be a replacement if you don't want to download git and does the same thing as it too. 
2. Create a [github](link) account. This is where all your remote repositories will be located in. If you decided to create a c9 account, you can link it with github. This means that you can log in c9 with your github username and password.
3.  SSH key is used to connect repos
