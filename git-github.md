[Return to Table of Contents](README.md)

# Class 3: Git v. Github

[Link to source material](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

*Key words:*
- VCS
- Git vs. Github
- local vs remote
- clone
- commit
- ACP (Add - Commit - Push)
- deployment

**Version Control**
1.	Allows for easy rectification of mistakes with files
2.	Can track modifications and modifying individuals, comparing changes
3.	Can revert a file or project to a previous version

**Centralized Version Control**
1.	Provides a streamlined collaboration process for multiple programmers
2.	Additional authority for admins who want to control revision privileges

**Distributed Version Control**
1.	Addresses major vulnerability of CVS (server is single point of failure, potential lack of backup)
2.	Allows for multiple mirrored repositories, enabling simultaneous workflows

### What is Git?

Git is a DVCS that stores data in a file system made up of snapshots. Every time you make a change, it captures that “moment in time” so to speak. Because every single change is tracked, Git will always detect file corruption or loss of information. Git allows for “non-linear development via multiple branches, [can] support large projects, [possesses] strong mechanisms preventing corruption, and [has] a simple design. 

**Files** - Files in Git can reside in three main states: committed, modified, and staged.
* *Committed* - data is securely stored in a local database
* *Modified* File has been changed but not committed to the database
* *Staged* - flagged a file’s changed version to be committed in the next snapshot

Here are 3 Options for Installing Git for Mac OS
1.	Run Git from the Terminal
1.	[Git website](https://git-scm.com/download/mac) provides directions for downloading Git.
1.	Install Git as part of the [GitHub for Mac install.](https://desktop.github.com/) 

You can access a variety of GUI clients for Mac, Windows, and Linux via this link: https://git-scm.com/downloads/guis

***Workflow**
**Local Repository Structure**
The local Git repository has three components:
1.	Working Directory: the actual files reside here.
2.	Index: The area used for staging
3.	Head: Points to the most recent commit

Files are *tracked* or *untracked*. 

To check file status, utilize the `git status` command.

Track one file only - `git add filename`

Track all files in a repository - `git add *`

Committing a File - `git commit -m “made change x,yz”

Committing all changes - `git commit -a`

Pushing changes - `git push origin master`

**Stashing changes** - `git stash` (and then when ready, `git stash apply`)

### Remote Repositories

Teams can use remote repositories to push information to and pull data from.

*Cloned Repositories* - Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch

*Seeing Your Remotes*
To view the short names, such as “origin” you can run the `git remote` command

Using `git remote –v` you can view all the remote URLs next to their corresponding short names

```
$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)
```

[Previous - Tools & Terminal Notes](tools-terminal.md)

[Next - Class 3 Stretch](lab03-stretch.md)
