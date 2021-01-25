# Version Control
is a system that allows you to revisit various versions of a file or set of files by recording changes,
by utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS), If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories to replace any lost information.

# Git
#### Files in Git can reside in three main states:
1. Committed : Data is securely stored in a local database
1. Modified : File has been changed but not committed to the database
1. Staged : Flagged a file’s changed version to be committed in the next snapshot

![Git](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

### Download Git
###### Git can be installed in three ways:
1. Install as a package
1. Install via another installer
1. Download and compile the source code.

###### method for installing Git with Mac OS X:
- running Git from the Terminal. If Git is not installed, you will see a prompt for installation.
- You can also download Git by visiting this link "http://git-scm.com/download/mac".
- Download GitHub for Mac via ththis link "http://mac.github.com".

###### method for installing Git with Windows:
- You can download Git by visiting this link "http://git-scm.com/download/win".
- Install Git as part of the GitHub for Windows install "http://windows.github.com".

###### method for installing Git with Linux:
- For Fedora: $ sudo yum install git
- For Ubuntu: $ sudo apt-get install git
- To download Git for Linux, visit this link "http://git-scm.com/download/linux"

#### Graphical Clients
You can access a variety of GUI clients for Mac, Windows, and Linux via this link: "https://git-scm.com/downloads/guis"

##### Initial Customization
- Configuration of Variables : Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.
- Identity Setting :
Type the following into Terminal or Command Line:

git config --global user.name "Jane Smith" git config --global user.email "example@email.com"

And to confirm that you have the correct settings:

git config --global user.name (should return Jane Smith) git config --global user.email (should return example@email.com)


# Setting up a Git Repository
##### Steps to import an existing project or directory into Git using the Terminal or Command Line:
- Switch to the target project’s directory: $ cd test (cd = change directory)
- Use the git init command: $ git init
- perform an initial commit to start tracking these repository files:
1. $ git add *.c
1. $ git add LICENSE
1. $ git commit -m “any message here”

#### Cloning
$ git clone https://github.com/test

# Workflow

### Local Repository Structure
#### The local Git repository has three components:
1. Working Directory: The actual files reside here.
1. Index: The area used for staging
1. Head: Points to the most recent commit

Saving Changes
- Tracked
- Untracked

![workflow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

#### The Life Cycle of File Status
After you edit a file, Git flags it as modified because of changes made after the previous commit,You stage the modified file Then, you commit staged changes.

#### Check File Status
To determine the state of files $ git status

![life cycle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

