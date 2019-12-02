# GitHub Tutorial (2019)

*by Ze Zhen Yang*

---
## Git vs. GitHub
- Git is independent from github that is use for version controls and create repositories
- Github depedents on git, it is a website that lets you better manage your repositories


---
## Initial Setup
- To set up a github account, go [here](https://github.com/join?source=header-home). 
- Setting up IDE (on ide.cs50.io), go [here](https://github.com/hstatsep/ide50).
    - Just follow the direction about generating and connecting a SSH key between IDE and github to setup the IDE. 
    - It is always important to connect a SSH key when setting up a new IDE with github because this way you won't have to login everytime you want to use the IDE.
        - A SSH key is like a ID card, by providing the key to the IDE it allows you to access your repository as long as you are login on github.

---
## Repository Setup



---
## Workflow & Commands
- git status
    - pretty much just show the files that has been edited or changed
- git add
    -  put the file(s) onto the staging step
        - the staging step is the step before being commited, to ensure that you want to commit this file
    - git add filename
        - adds a single file, can add more when a space (git add filename filename)
    - git add .
        - adds every files in the **CURRENT** directory/folder
    - git add -A
        - similar to "git add .", but **ADDS EVERYTHING** (files & directory) outside and inside the current directory
- git commit
    - saves changes or staged files to the local repository (the IDE you are using right now)
    - git commit -m "message"
        - git commit is usually used with -m to stand for message, where you give the commit a name so it will be easier to look for if you every go back
        - when naming, it will help by using present tense, lower case, and the main change of the file
- git push
    - upload or saves the commit file to a remote repository (in this case it will be github)
    - to use "git push" you will have to set it up using "git push -u origin master"

---
## Rolling Back Changes
