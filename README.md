# 📖 Overview
This assessment demonstrates core Git and GitHub workflows including:

1. Repository initialization
2. Tracking and committing changes
3. Branching and merging
4. Handling errors using stash, reset, and revert

# 📦 GitHub Assignment 
**Question 1: Project Initialization & First Push**

## Objective
Set up a new Git project and push it to a remote repository.

## Steps

```VS Code Terminal (CTRL + J)
#Create a new folder for your project
mkdir Git_Github_Assignment
cd Git_Github_Assignment

# Initialize Git repository
git init

#Create a file named app.py and add some Python code
echo "print('Hello, This is a python file... for github assignment')" > app.py

#Check the current Git status
git status

#Stage the file
git add app.py

#Commit with a meaningful message
git commit -m "Initial commit: added app.py"

#Create a remote repository
* Go to GitHub
* Create a new repository
* Copy the repository URL

#Add the remote (origin) to your local repo
git remote add origin https://github.com/rahulchidambaram/Github_Assignment.git

#Verify the remote configuration
git remote -v

#Push your code to the remote repository
git branch -M main
git push -u origin main

```
