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
benrjg@BenRJG:~/Desktop/UbuntuSetup$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   GitSetup.md

no changes added to commit (use "git add" and/or "git commit -a")


**git commit file.md**
benrjg@BenRJG:~/Desktop/UbuntuSetup$ git commit GitSetup.md 
[master 0c002ad] Added Version Tracking Tutorial
 1 file changed, 16 insertions(+)

Add to local repository
-----------------------
**cd directory**
**git remote add origin https://github.com/NodrogJRB/UbuntuSetup.git**

**git config --global push.default simple**
**git push --set-upstream origin master**
**git push -u origin**

from now on can just use
**git push**

Using Markdown
--------------
