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







