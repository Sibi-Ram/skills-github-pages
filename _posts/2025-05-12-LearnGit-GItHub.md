---
title: "Learn Git- GitHub"
date: 2025-05-12
---

# Essential Git and GitHub Commands
Git and GitHub are fundamental tools for version control and collaborative software development. Below are the most important and necessary commands every developer should know, along with their purposes.

## Initialize and Configure

**git init**: Initialize a new Git repository in your project folder.

**git config**: Set your user name and email (identity) for commits, e.g.,
**git config --global user.name** "Your Name"
**git config --global user.email** "your@email.com".

## Basic Workflow

**git status**: Show the current status of files in the working directory and staging area.

**git add <file>**: Stage changes (add files to the staging area) for the next commit.

**git commit -m "message"**: Save your staged changes locally with a descriptive message.

**git log**: View the commit history for the repository.

## Working with Remote Repositories (GitHub)

**git clone <repo-url>**: Make a local copy of a remote repository.

**git remote add origin <repo-url>**: Link your local repository to a remote one (often named origin).

**git push**: Upload your commits from your local repository to the remote repository (GitHub).

**git pull**: Download and merge changes from the remote repository to your local repository.

**git fetch**: Download changes from the remote repository but do not merge them automatically.

## Branching and Merging

**git branch**: List, create, or delete branches.
**git branch <branch-name>** creates a new branch.

**git checkout <branch-name>:** Switch to another branch.

**git merge <branch-name>:** Merge changes from another branch into your current branch.

**git branch -d <branch-name>:** Delete a local branch.

**git push --delete origin <branch-name>:** Delete a remote branch on GitHub.

## Other Useful Commands

**git rm <file>:** Remove a file from the working directory and stage the removal for commit.

**git show:** Display detailed information about a specific commit, including changes made.

**git diff:** Show differences between files or commits.

**git stash:** Temporarily save changes that are not ready to be committed.

## Key Concepts

**Repository:** A project folder tracked by Git.

**Branch:** An independent line of development, useful for features or bug fixes.

**Commit:** A snapshot of your project at a specific point in time.

**Push/Pull:** Sync changes between your local and remote repositories (e.g., GitHub).

**Merge:** Combine changes from different branches.

