# Git & GitHub Hands-on — Day 1

##  About This Practice

This repository is part of my **Git & GitHub hands-on learning journey**.

In Day 1, I started learning the basics of **Git and GitHub** and practiced the
complete basic workflow on my own system.

Through this practical, I learned how to initialize a Git repository, track files, stage changes,
create commits, check commit history, connect a local repository with GitHub, and push my code to a remote repository.

This is the beginning of my Git & GitHub practice, and I will
continue adding more concepts and hands-on activities as I progress.

##  Day 1 Objective

The main goal of Day 1 was to understand the basic Git workflow and perform my first GitHub push.

### What I practiced:

- Git repository initialization
- Checking repository status
- Staging files
- Creating commits
- Viewing commit history
- Connecting local Git with GitHub
- create repository
- Working with the `main` branch
- Pushing changes to GitHub


##  Basic Git Workflow

Working Directory
       ↓
   git add
       ↓
 Staging Area
       ↓
  git commit
       ↓
Local Repository
       ↓
  git push
       ↓
    GitHub


## commands:

* git init
* git status
* git add .
* git commit -m "initial commit"
* git log --oneline
* git remote add origin <repository-url>
* git branch -M main
* git push -u origin main


# Day 2: Git Changes Practice

This is my Day 2 hands-on practice of Git and GitHub as part of my AWS Cloud and DevOps learning journey.

### Topics Covered

* `git status`
* `git add`
* `git diff`
* `git diff --staged`
* `git restore`
* `git restore --staged`
* `git commit`
* `git log --oneline`

### Learning Outcome

I learned how to track file changes, stage modifications,
undo unwanted changes, and manage Git commits.



# Day 3: Git Branching Practice

## About
- my Day 3 Git hands-on practice as part of my AWS Cloud and DevOps learning journey.

## Topics Covered
- Creating a branch using `git branch`
- Switching branches using `git switch`
- Checking branches using `git branch`
- Checking file status using `git status`
- Staging changes using `git add`
- Committing changes using `git commit`
- Checking commit history using `git log --oneline`

## Practical Work
Created a separate branch, made changes to a file, and committed the changes.
Then switched between branches to understand how changes are maintained separately.

## Learning Outcome
I learned how Git branches work and how to make changes in a separate branch without directly modifying the main branch.



# Day 4: Git Branching and Merge

## About
- my Day 4 Git hands-on practice of git branching

## Topics Covered
- Creating a new branch
- Switching between branches
- Checking file status
- Staging and committing changes
- Merging a feature branch into the main branch
- Checking commit history

## Practical Work
Created a `feature` branch and added changes to a file. After committing the 
changes, switched to the `main` branch and merged the feature branch into it.

## Commands Practiced
- `git init`
- `git branch`
- `git switch`
- `git status`
- `git add`
- `git commit`
- `git merge`
- `git log --oneline`

## Learning Outcome
I learned how to merge changes from a feature branch into the main branch using Git.

# Day 5: GitHub Remote Repository Practice

## About
 Day 5 of Git and GitHub hands-on practice as part of my AWS Cloud and DevOps learning journey.

## Topics Covered
- Understanding local and remote repositories
- Connecting a local Git repository to GitHub
- Adding a remote repository using `git remote add`
- Checking remote repository details using `git remote -v`
- Renaming the current branch to `main`
- Pushing local commits to GitHub using `git push`

## Practical Work
Created a local Git repository and practiced preparing it for connection with a 
GitHub remote repository. The goal is to understand how local project files and
commits can be uploaded to GitHub.

## Commands Practiced
- `git init`
- `git status`
- `git add`
- `git commit`
- `git remote -v`
- `git remote add origin`
- `git branch -M main`
- `git push -u origin main`

## Learning Outcome
I learned the basic workflow of connecting a local Git repository to 
GitHub and uploading local commits to a remote repository.



# Day 6: Git Pull and Fetch Practice

## About
- Day 6 Git and GitHub hands-on practice as part of my AWS Cloud and DevOps learning journey.

## Topics Covered
- Understanding Git Fetch
- Understanding Git Pull
- Understanding Git Clone
- Synchronizing local and remote repositories
- Checking remote repository details
- Reviewing Git commit history

## Commands Practiced
- `git init`
- `git add`
- `git commit`
- `git remote -v`
- `git fetch origin`
- `git pull origin main`
- `git clone`
- `git status`
- `git log --oneline`

## Practical Work
Created a separate local Git repository and practiced preparing it for connection to GitHub. The objective is to understand how to fetch remote updates and integrate them into the local repository.

## Learning Outcome
I learned the difference between `git fetch`, `git pull`, and `git clone`, 
and how these commands help manage changes between local and remote repositories.

## Key Difference
- **Git Fetch:** Downloads remote updates without integrating them into the current branch.
- **Git Pull:** Downloads remote updates and integrates them into the current branch.
- **Git Clone:** Creates a local copy of an existing remote repository.



# Day 7: GitHub Pull Request and Collaboration

## About
This repository contains my Day 7 Git and GitHub learning notes as part of my AWS Cloud and DevOps learning journey.

## Topics Covered
- Understanding GitHub collaboration
- Feature branches
- Pull Requests (PR)
- Pull Request workflow
- Code review
- Merging Pull Requests
- Difference between Git Merge and Pull Request
- Forking a repository
- GitHub Issues

## Important Concepts
- Creating a feature branch
- Pushing a branch to GitHub
- Creating a Pull Request
- Reviewing code changes
- Discussing and approving changes
- Merging a Pull Request

## Learning Outcome
I learned how developers collaborate on GitHub using branches and Pull
Requests, and how code reviews help maintain code quality.

## Purpose
To understand the basic collaboration workflow used by
development and DevOps teams in real-world projects.




# Day 8: Git Workflow and Gitignore

## About
This repository contains my Day 8 Git and GitHub learning notes as part of my AWS Cloud and DevOps learning journey.

## Topics Covered

### 1. Git Workflow
- Understanding the Git workflow
- Checking repository status
- Viewing file changes
- Understanding commit history
- Renaming and removing files
- Restoring file changes
- Temporarily saving changes using Git Stash

### 2. Gitignore
- Understanding the `.gitignore` file
- Why `.gitignore` is needed
- Ignoring files and folders
- Ignoring log files and temporary files
- Ignoring environment and configuration files
- Common `.gitignore` patterns

## Important Commands
- `git status`
- `git diff`
- `git diff --staged`
- `git log --oneline`
- `git show`
- `git restore`
- `git mv`
- `git rm`
- `git stash`
- `git check-ignore`

## Learning Outcome
I learned how to manage file changes, review commit history, temporarily save 
uncommitted work, and prevent unwanted files from being tracked using `.gitignore`.

## Purpose
To understand a clean Git workflow and learn how developers manage project
files safely and efficiently in real-world development environments.



# Day 9: Git Merge Conflict Resolution and Git Stash

## About
This repository contains my Day 9 Git and GitHub learning notes as part of my AWS Cloud and DevOps learning journey.

## Topics Covered

### 1. Git Merge Conflict Resolution
- Understanding merge conflicts
- Common causes of merge conflicts
- Understanding conflict markers
- Resolving conflicts manually
- Staging and committing resolved files
- Aborting a merge
- Real-world merge conflict scenarios

### 2. Git Stash
- Understanding Git Stash
- Temporarily saving uncommitted changes
- Viewing saved stash entries
- Applying and removing stash entries
- Difference between `git stash pop` and `git stash apply`
- Stashing untracked files

## Important Commands
- `git status`
- `git diff`
- `git merge --abort`
- `git stash`
- `git stash list`
- `git stash pop`
- `git stash apply`
- `git stash drop`
- `git stash clear`
- `git stash -u`

## Learning Outcome
I learned how to identify and resolve Git merge conflicts and how to temporarily save uncommitted changes using Git Stash.

## Purpose
To understand common Git challenges and learn how to manage changes effectively while 
working with branches and collaborating with other developers.


# Day 10 – Git Reset and Git Revert

## Overview
This document covers Git Reset and Git Revert, two important Git commands used to undo changes and manage commit history.

## Topics Covered
- Introduction to Git Reset
- Types of Git Reset
  - Soft Reset
  - Mixed Reset
  - Hard Reset
- Introduction to Git Revert
- Difference between Git Reset and Git Revert
- Real-world scenarios
- Git interview questions

## Git Reset
Git Reset is used to move the current branch to an earlier commit and manage changes in the staging area and working directory.

### Types of Git Reset

**1. Soft Reset**
- Moves the branch to an earlier commit.
- Keeps changes staged.

**2. Mixed Reset**
- Moves the branch to an earlier commit.
- Removes changes from the staging area.
- Keeps changes in the working directory.

**3. Hard Reset**
- Moves the branch to an earlier commit.
- Resets the staging area.
- Discards changes to tracked files in the working directory.

## Git Revert
Git Revert is used to undo the changes introduced by a previous commit by creating a new commit.

It is useful when working with shared repositories because it preserves the existing commit history.

## Git Reset vs Git Revert

| Git Reset | Git Revert |
|---|---|
| Moves the branch pointer | Creates a new commit |
| Can rewrite commit history | Preserves commit history |
| Useful for local changes | Useful for shared repositories |

## Real-World Use Cases
- Undoing an incorrect local commit.
- Removing files from the staging area.
- Discarding unwanted local changes.
- Reversing incorrect changes pushed to GitHub.
- Maintaining a clear commit history.

## Learning Outcome
After studying these topics, I understood how Git Reset and Git Revert work,
their differences, and when to use them in real-world development.

## Conclusion
Practicing Git Reset and Git Revert helps me understand how to manage mistakes,
undo changes, and maintain commit history while working with Git and GitHub.


