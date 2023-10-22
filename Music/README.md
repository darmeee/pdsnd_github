Git Workflow Documentation
This document provides a step-by-step guide on using Git to clone a repository, add, commit, create branches, and push changes to a remote repository. The following steps walk you through the process of using Git for version control.

Cloning a Repository
Open a command prompt or terminal on your local machine. In this example, we are using Windows Command Prompt.

Navigate to the directory where you want to clone the Git repository. You can use the cd command to change directories.
cd C:\Users\damilolaoke

To clone a Git repository, use the git clone command followed by the repository's URL. https://github.com/udacity/pdsnd_github
git clone https://github.com/darmeee/pdsnd_github

This will create a local copy of the repository in a folder named pdsnd_github.
Adding and Committing Files
Before adding and committing files, make sure you have the files you want to add in your local repository directory.

To add files to the staging area, use the git add command.
git add bikeshare.py
git add bikeshare.txt

Once the files are staged, you can commit the changes with a meaningful commit message.
git commit -m "Added bikeshare.py and bikeshare.txt"

Creating and Pushing a Branch
To create a new branch, use the git checkout -b command. 
git checkout -b documentation

You can now push the branch to the remote repository.
git push origin documentation

To switch back to the master branch, use the git checkout command.
git checkout master

Refactoring Code in a Branch
To create a new branch for code refactoring, use the following commands:
git checkout -b refactoring

After making your code changes, stage and commit the files.
git add bikeshare.py
git commit -m "Refactored code for better efficiency and readability"

Push the refactoring branch to the remote repository.
git push origin refactoring

To switch back to the master branch:
git checkout master

Pulling Changes from Remote
To update your local master branch with changes from the remote repository:
git pull origin master

Now you have successfully cloned a repository, added and committed files, created branches, and pushed changes to a remote repository using Git.