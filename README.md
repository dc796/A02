# A02 Git, WebStorm, and GitHub: step-by-step Tutorial

Goal: is to create a **GitHub** **repository** named A02, and learn how to use **Git**, Webstorm, and **GitHub**.


## Prerequisites (On what you need to install)
1. Webstorm (IDE): download from JetBrains.
   page: https://www.jetbrains.com/webstorm/download/download-thanks.html 

2. **Git** (Command line): 
   page: https://git-scm.com/downloads

3. **GitHub** account: Sign up for one and create an account
   page: https://github.com


# Part 1: Using Webstorm + Git + GitHub

## A. Create a GitHub account and repository examples

1. Go to https://github.com and sign up for an account.
2. Log in. In the upper right corner and click on the + icon for New **repository**.
3. **Repository** name: A02 (It can be any name depending on the situation)
4. Choose public
5. Click on Create **repository**. You will get the link, e.g., https://github.com/yourUCID/A02. (Or your username) Save it, then send the link to others.

## B. Install WebStorm, Git, and link accounts to WebStorm.
1. Download and install WebStorm from JetBrains.
   https://www.jetbrains.com/webstorm/download/download-thanks.html
2. Download and install **GIT** from https://git-scm.com/downloads. After installing it, open up the terminal to check the version.
   git --version
4. Setting up **Git** in Webstorm: Go to VCS --> Enable Version Control Integration.
5. Add **Github** Account: Go to File --> Settings, navigate to Version Control --> click + --> Then place login credentials.


##  Workflows
### Workflow - using Webstorm
1. Open up WebStorm
2. File --> New Project --> choose a project type or file --> Open to open an existing folder.
3. Enable Version Control: VCS --> Enable Version Control Integrations --> Choose **GIT**.
4. If the project folder is not yet a **Git** repo: Webstorm will offer to make to create a **Git** **Repository** (git init)
5. Makes Files/changes. In the **Commit** window, stage files and write a clear **commit** message. Click **Commit**
6. To add a **remote**, VCS --> **Git** --> **Remotes** and add origin with your repo URL (e.g., https://Github.com/yourUCID/A02.git)
7. Use **Push** to send **commits** to **GitHub**. Use Pull to **fetch** and **merge** **remote** changes locally.


# Part 2 - Glossary

* **Branch** - A separate line of development in Git. Branches let you work on features independently and later can merge back into the other branches.

* **Clone** - A full copy of a remote repository on the local machine (includes the history of commits) 

* **Commit** - A saved snapshot of stage changes in the repository; has an author, timestamp, and message. 

* **Fetch** - Download commits, files, and refs from a remote repository, but do not merge them automatically into your working branch. 

* **GIT** - The distributed version control system used to track changes and coordinate work among other developers.

* **GitHub** - Web hosting service for Git repositories that adds collaboration, issue tracking, pull requests, and a web UI.

* **Merge** - Combine changes from one branch into another. 

* **Merge Conflict** - A situation where Git cannot automatically combine changes from two commits because the same lines/files were edited differently and require a resolution. 

* **Push** - Upload a local commit to a remote repository 

* **Pull** - Fetch changes from a remote and automatically merge them into your current batch. 

* **Remote** - A reference to a repository hosted elsewhere is usually the GitHub repo.

* **Repository** - A project container that holds files, folders, and the entire commit history. 


# Citations/References
* Jet Brains - WebStorm download: https://www.jetbrains.com/webstorm/download/?section=windows
* Jet Brains - WebStorm (Getting Started): https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html 
* Git - https://git-scm.com/downloads
* GitHub Docs (Getting Started) - https://docs.github.com/en/get-started/git-basics/set-up-git
* GitHub Docs (Revolving Merges)- https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github 
* GitHub Docs (Making a repository) - https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories
* 
