# 📖 Overview
This repository demonstrates core Git and GitHub workflows including:

1. Repository initialization
2. Tracking and committing changes
3. Branching and merging
4. Handling errors using stash, reset, and revert

# 📦 GitHub Assignment 
**Question 1: Project Initialization & First Push**

## Objective
Set up a new Git project and push it to a remote repository.

## Scenario
You are starting a new Python project. You need to track your work using Git and upload it to a remote repository.

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

**Question 2: Working with Changes & History**

## Objective
Track code changes and manage commit history properly.

## Scenario
You are enhancing your existing app.py application with new features.

## Steps
```
#Modify app.py by adding new functionality
#Open app.py and add a new functionality
echo "print('Added a new feature')" > app.py

#Check what changes are made before staging
git status

#View differences in the file
git diff

#Stage only specific changes (if possible)
git add -p

#Commit with a clear message
git commit -m "added new functionality"

#Make another change in app.py
echo "print('This is a new change')" > app.py

#Stage all changes
git add .

#Commit again
git commit -m "Updated app logic"

#View full commit history
git log

#View compact (one-line) history
git log --oneline
```

**Question 3: Branching & Feature Development**

## Objective
Work with branches and manage feature development.

## Scenario
You are developing a new feature separately to avoid affecting the main code.

## Steps
```
#Create a new branch (e.g., feature-update)
git branch feature-update

#Switch to the new branch
git checkout feature-update

#Modify app.py with new feature logic
echo "print('This is a new change from feature branch')" > app.py

#Stage and commit the changes
git add .
git commit -m "Added new logic from feature branch"

#Switch back to the main branch
git checkout main

#Merge the feature branch into main
git merge feature-update

#Verify changes are merged
git log --online

#Delete the branch safely
git branch -d feature-update
git branch

#create a dummy branch for this
git branch dummy-branch

#Force deleting a branch
git branch -D dummy-branch
 
```
