# GitHub Tutorial

_by Cindy Li_

---
## Git vs. GitHub
Git is a version of a control system, that helps you keep track of changes of file over time. EX. _"Git is a version control system which "tracks changes" for code."_.

GitHub is a "cloud" that help make things easier to work with. Github allows us to see all of our repositories in one place and you can manage them by sharing,replying,editing,and track them, etc all in one place.

The difference between Git and Github is that Git is a local system while Github is a "Cloud" that you can share, reply, edit and track codes that you have created.


---
## Initial Setup
* Create a [**github account**](https://github.com)
* IDE is a cloud based that allows you to build your code into website format and publish any format you design.
* To setup on _ide.cs50.io_ by follow this link: [**set-up ide.cs50.io**](https://github.com/hstatsep/ide50)
* To use IDE, make sure to log in to [github.com](www.github.com) before going to [IDE](www.ide.cs50.io)


---
## Repository Setup

# Before building your ide, make sure to alway go to github.com and create a new repository.
* By creating a new repository, you have to first go to [github](github.com).
* On the upper right corner, you click the "**+**" sign.
* Then you click "**New repository**" and create the repository name (make sure to be the exact same thing that you create in your IDE).
* Once you press "**create**", now you go to your [IDE](www.ide.cs50.io)

# Once you're in your IDE, start by:
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
*  * git init helps you initialize the terminial into github so you can add your information into github.com
* **git add file** - Add to the staging area
  * git add file helps you add your file in to the staging area so the ide know where you put your information.
* **git commit -m "message"** - Permanently stores changes from the staging area inside the repository by a message
  * git commit -m helps you add a permanently stores change by adding a message
* **git push** - Used to upload local repository in to  remote repository.
  * git push is used to upload your ide in to your github
* **git diff** - Checks difference between the working directory  and the staging area
* **git log** - Chronologically on the resportitory. Shows all previous commits
* **git checkout -- file** - Rewrite the line but forgot the exact. Discard changes in working directory
* **git reset HEAD file** - Able to upstage the file from the staging area
* **git status** - To see when it was last commited. It can also use for a command to see which files have been edited since the last commit (they will be red) or a command to see which files are staged for the commit (they will be green)
* **git revert** - Works by undoing changes that were made in the specified by commit by creating another new commit and not actually removing any previous commits. This is ideal for published changes because the true history of the repo is preserved.

# To add your IDE into your github
* You first git init, git init helps you initialize the terminial into github so you can add your information into github.com.
* Then you git add file, git add file (most likely git add README.md), git add file helps you add your file in to the staging area so the ide know where you put your information.
* After git add file, you git commit -m, it helps you add a permanently stores change by adding a message.
* Then you git push, git push allow you to push your ide into your github.

### Feedback 
 You did really well at explaining the steps.
 You provided links to further help the user so good.
 I suggest you to add more italics. 