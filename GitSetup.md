Git
====
Installing Git
--------------
**sudo apt install git** in console
'''
benrjg@BenRJG:~/Desktop/UbuntuSetup$ sudo apt install git
[sudo] password for benrjg: 


Initialising Repository
-----------------------
**git init** in console
benrjg@BenRJG:~/Desktop/UbuntuSetup$ git init
Initialised empty Git repository in /home/benrjg/Desktop/UbuntuSetup/.git/

Setting up Git User Account
---------------------------
**git config user.name "Firstname Surname"**
**git config user.email "Email"**

Adding new file to git
----------------------
**git add** ***file*** **.md**

Commit repository
-----------------
**git commit**
enter commit message
ctrl + O to save
ctrl + O to exit
benrjg@BenRJG:~/Desktop/UbuntuSetup$ git commit
[master (root-commit) b13145a] Added Contents, GitSetup and Install files
 3 files changed, 44 insertions(+)
 create mode 100644 Contents.md
 create mode 100644 GitSetup.md
 create mode 100644 Install.md

**git log** shows log of changes

Version Tracking
----------------
**git status** to see changes made

**git commit file.md**

Using Markdown
--------------
