# GitHub Tutorial

_by Josue Moran_

---
## Git vs. GitHub
* For Starters  
    * **Git** is the tool that lives on your workspace, to help you save snapshots of your code.
        * For intance, if you decide to change the whole layout of a page but decide it looks horrible, you can always reffer to a prevouis snapshot.
    * **Github** on the other hand, is an online website that harbors all these snapshots as an open source platform.
        * It allows people to collabrate on projects by pulling and pushing projects to and from the cloud, which is cloning and adding suggestions. 

---
## Initial Setup
To initialy set up your _worspace_  you must

* Create an account with [GitHub](https://www.github.com). Its very simple and should only take no more than 2 minutes.
* Next you'll want to open up your editor that you're using to write code, for this example we'll use [Cloud9](https://www.c9.io)
* Navidate to settings, assuming you already have an account registered, and look for SSH keys
* Once you it copy the whole key and paste it to your github account in the ssh keys section of settings
* don't forget a tittle
* Now that you have that setup you now have a connection betwwen your C9 account and github.
* Now navigate to your workspace and make sure your in the right directory
* you'll want to be inside "workspace" which you can always reach by typing "cd .." into the console.
* Now set up github on your worspace by typing 
```
config --global user.name "Your First Name Last Name"
```
and then
```
git config --global user.email "email address"
```

---
## Repository Setup
####Setting up a Repository is simple
* Firs you open uo github and on the right side there is a create new repository button
* click that and give it a name
* once it has a name and it is created, open it up and click clone
    *but make sure it is on ssh not https
* now type 
```
git clone "URL"
```
* and paste the url
* This will now clone the newly created repostory into your worspace




---
## Workflow & Commands
###Always remember these commands
```
git status
```
* checks the status of the directory, you shoul do this often to know if you've added any files t the stage or if you've cmmmitted

```
git add "File Name" or git add . or git add all
```
* yu can use either one to add a file ready to be commited
    * the first one only adds a specific file 
    * the second and third one adds all files in that directory

```
git commit -m "message"
```
* this takes a snapshot of your code but rememeber a short message in the present tense

```
git push
```
* this is the final command that you use to push that snapshot back to your github account

