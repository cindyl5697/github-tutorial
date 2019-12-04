# GitHub Tutorial

_by Cindy Li_

---
## Git vs. GitHub
Git is a version control system, that helps you keep track of changes of file over time. EX. **"Git is a version control system which "tracks changes" for code."**
GitHub is a cloud that help make things easier to work with. Github allows us to see all of our repositories in one area and manage them (share,reply,edit,and track them, etc) in one place.
The difference between Git and Github is that Git is a local system while Github is a "Cloud" that you can share, reply, edit and track codes that you have created.


---
## Initial Setup
* Create a [**github account**](https://github.com)
* Setup on _ide.cs50.io_ by going to this link [**ide.cs50.io](www.ide.cs50.io)


---
## Repository Setup

* Go home by using **cd ~**.
* Then go to github-learning by using **cd github-learning**.
* Make a directory _repotest_ (the directoryname)  in github-learning using **mkdir repotest** .
* Go into the directory repotest by using **cd repotest**.
* Make README.md file by using **touch README.md**.
* You init by using **git init**.
* Then you go into the README file by using **c9 README.md**.
* You write the steps inside the file (README.md).
* You save the file by using **command s**.
* After that you go back to the terminal where the code is.
* Add README.md in Terminal by using **git add README.md**.
* After you add, you commit the file by using **git commit -m "the message"**.
* Then you go to github and use the links from push section.
* Copy the **"add orgin..."** into the terminal.
* Then copy **"git push -u.."** into the terminal.
* Then you will see that the README message (the one you're reading right now). is in the website github.com


---
## Workflow & Commands
* **git init** - Initialize the terminial
* **git add file** - Add to the staging area
* **git commit -m "message"** - Permanently stores changes from the staging area inside the repository by a message
* **git diff** - Checks difference between the working directory  and the staging area
* **git log** - Chronologically on the resportitory. Shows all previous commits
* **git commit -m "message"** - Permanently stores changes from the staging area inside the repository by a message
* **git diff** - Checks difference between the working directory  and the staging area
* **git log** - Chronologically on the resportitory. Shows all previous commits
* **git checkout -- file** - Rewrite the line but forgot the exact. Discard changes in working directory
* **git reset HEAD file** - Able to upstage the file from the staging area
* **git status** - To see when it was last commited. It can also use for a command to see which files have been edited since the last commit (they will be red) or a command to see which files are staged for the commit (they will be green)
* **git revert** - Works by undoing changes that were made in the specified by commit by creating another new commit and not actually removing any previous commits. This is ideal for published changes because the true history of the repo is preserved.


