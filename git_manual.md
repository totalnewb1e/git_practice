# *GIT_MANUAL* **after the installation**

## **Call terminal by using CTRL + ` hotkey**

**step 1.** make sure u intredused urself by using :

* **git config --global user.name "name"**

* **git config --global user.email "email"**

**step 2.** git init - git repository initialization in the root folder.

**step 3.** use CTRL + S anytime u wanna save ur changes.

**step 4.** use **git add (tab to chose file name)** to add changes to the file.

**step 5.** use **git commint -m "message"** to leave a message to ur commit.
___________________________________

### *USEFULL_COMMANDS*

* **git log** - checking latest commits

* **git status** - current git status (branch, commits etc.)

* **git checkout** - commit hopping from master to others

* **clear** - clearing terminal

* **git mv** - renaming files

* **git --help** - to see all of the helpfull commands

_______________________________

*[Git for IT book](https://gbcdn.mrgcdn.ru/uploads/asset/4245110/attachment/d4eb8c232f8f2bdf4e42ba7cb49e0c50.pdf)*.


*[YT video for Git beginners](https://www.youtube.com/watch?v=8JJ101D3knE)*.

![Barbara](IMG_20151212_113525.jpg)

*[YT video for Git beginners](https://www.youtube.com/watch?v=8JJ101D3knE)*.\

### **commands for branches**

* git branch branch_name - crating new branch
* git branch -d branch_name - deleting branch
* git checkout -b branch_name - creats new branch and switching to it

## gonna work this time

**_there's 3 types of conflicts_**

1. fast-forward - merging work for branch_name to empty master branch

2. 'ort' - auto-merging w/o a conflict

3. conflit - merging with current/incoming or both changes
_____________________

* <<<<<<<<<< HEAD till ======= is current changes 

* ======== till >>>>>>>>>> branch_name is incoming changes

compare is comparing changes in a new window ! does not merging them

## working with  **_github_**

To work with github properly u've to create an acc at [Github](github.com)

create a new repo at [Github](github.com) (choose + >> new repo at right corner of ur screen)

then connect ur local repo and remote repo by useing tips at [Github](github.com)

* echo "# 123" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/totalnewb1e/123.git
git push -u origin main

* git remote add origin https://github.com/totalnewb1e/123.git
git branch -M main
git push -u origin main

_________________

To work w repos that u doesnt own u've to fork them by clickin fork button at some1s repo at [Github](github.com) - that makes a clone of a repo on ur acc at [Github](github.com)

then u can pull a cloned repo to ur PC and work w it as a local repo

### **commands**

* git push - pushin changes to remote repo

* pit pull - pullin changes to local repo

**dont forget to commit them**

### comparing and pull requesting

after u did some work at cloned repo u can pull a request to owner of a repo by pushin ur branch **!dont forget to commit changes**

gg. well done. ur beautiful