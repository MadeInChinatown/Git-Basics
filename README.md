# Git Basics

**TLDR:** Git is a version control system. Git is used to track changes, backup, keep a version history of all your project files somewhere online. Use Git so you don't accidentally lose your code.  

These are the commands you need to know to get started:
* git clone
* git fetch
* git merge
* git pull
* git add
* git status
* git commit
* git push

To get started with learning the basics of Git, we recommend the following tools:
* GitHub (Git account)
* SourceTree (Git application/client)



## Why Get Git?

With Git, you can:
* Easily save and view your files somewhere online (that's not Google Drive)
* Change your files without needing to manually reupload them every time
* Keep a copy of all your changes

Why might this be helpful? Let's take a look at a few scenarios:

##### Scenario 1: Moving Files Between Computers

>You really like to use this one specific computer at work, so you write all your code and save all your files on this computer. Suddenly, the World Health Organization declares a global pandemic, and you now must quarantine yourself and work from home. Forgetting to grab the files before the office closed, you load up your computer at home and think "Oh no, all my files are on the computer at work! I wish I could just download them online...".

##### Scenario 2: Keeping a Change Log

>You decide that you want to make some major revisions to your code. You run your rewritten code and everything works perfectly. Now that your code has been restructured, you realize that there are about 100 lines of old code that no longer do anything, so you decide to delete them. The next day, you run your code and everything crashed! You realize you accidentally deleted an important part of your program yesterday! Whoops...now, what exactly was it that you deleted again? And how was it written? If only you could grab a copy of you code before the revisions!

I think you get the idea...




## Important Git Commands

To get started with using Git, you only really need to know these 8 commands. Any other commands, you can learn as needed.  

##### git clone

* Copies all project files from Git to your specified folder/directory
* Sets up Git for that folder/directory

##### git fetch

* Gets the most recent changes from Git
* Does **NOT** change anything on your current computer

##### git merge

* After "git fetch", updates all the files on your current computer with the changes

##### git pull

* "git fetch" and "git merge" in one command

##### git add

* "Stages" any files that were created, modified, or deleted

##### git status

* Shows which files were recently created, modified, or deleted
* Shows which files are "staged"

##### git commit

* Takes a snapshot of your project and saves your files at that point in time
* Only "staged" files will be saved
* Does **NOT** send your changes to Git

##### git push

* Send all new commits (snapshots) to Git




## Tools to Get Started

To get started with using Git, we recommend the two following tools:
* GitHub
* SourceTree

### GitHub
This account is where your project files and your changes will be saved. When you push files to or pull files, you will upload or grab the files from the GitHub servers. Why GitHub specifically? Because it's the most commonly used hosting platform. You are free to use other services as well, like BitBucket.

[Register for GitHub here.](https://github.com/join?source=header-home "GitHub")

### SourceTree

SourceTree is an application to make using Git easier. SourceTree's documentation on setting the application up is pretty thorough, so if you need steps to set up SourceTree, you can find their documentation [here](https://confluence.atlassian.com/get-started-with-sourcetree/install-and-set-up-sourcetree-847359043.html "SourceTree Setup"). Just make sure the account type/host is the correct one (GitHub in our case).  

Normally, you have to type out the Git commands in some sort of terminal, but SourceTree replaces all that with fancy buttons:

##### git clone

![](https://i.gyazo.com/7ad7227ecd240db95bb1ba5210276409.png "git clone")
<br/>
<br/>
<br/>

##### git add

![](https://i.gyazo.com/979c6f6d7677b32e2a02008a0d89692a.png "git add")
<br/>
<br/>
<br/>

##### git status

![](https://i.gyazo.com/f7cfdd69bc4c93416f6aa582b6e3a54f.png "git status")
<br/>
<br/>
<br/>


##### git commit

![](https://i.gyazo.com/a1fc03f6ec1f7716f9a17e7b7ffe47d0.png "git commit")
<br/>
<br/>
<br/>

##### The Rest (git pull, git push, git fetch, git merge)

![](https://i.gyazo.com/d493eb100ca765ec13613af4b67487ff.png "The Rest")
