# Assignment 2

This repository chronicles the completion of various Git tasks for an assignment.

## Setup a Remote Repository, Add a File, and Commit Changes

### Steps Executed:

1. *Setup Remote Repository:*
   - Created a new repository titled Assignment-2 on GitHub.
   - Initialized Git in the local directory using:
     bash
     git init
     
   - Linked the local repository to the remote GitHub repository with:
     bash
     git remote add origin https://github.com/lucky-the-racer/Assignment-2.git
     
   - Added a README.md file with initial content.
   - Staged the README.md file for commit:
     bash
     git add README.md
     
   - Committed the changes to the local repository:
     bash
     git commit -m "Initial commit"
     
   - Pushed the changes to the remote master branch:
     bash
     git push -u origin master
     

## Create a New Branch, Commit Changes, and Merge

### Steps Executed:

1. *Create and Switch to New Branch:*
   - Created and switched to a new branch named new-feature:
     bash
     git checkout -b new-feature
     
   - Made modifications to README.md (e.g., added "New Feature") and committed the changes:
     bash
     git add README.md
     git commit -m "Add new feature to README"
     
   - Pushed the new-feature branch to the remote repository:
     bash
     git push origin new-feature
     

2. *Merge New Branch with Master:*
   - Merged the new-feature branch into master using a pull request on GitHub.

## Undo Last Commit or Remove Last Created File

### Steps Executed:

1. *Undo Last Commit:*
   - Reverted the last commit with:
     bash
     git reset HEAD^
     

## Resolve Merge Conflicts

### Steps Executed:

1. *Handle Merge Conflicts:*
   - During the merge of new-feature into master, conflicts in README.md were resolved:
     - Manually edited conflicting sections in README.md to resolve conflicts.
     - Added the resolved file:
       bash
       git add README.md
       
     - Committed the resolved changes:
       bash
       git commit -m "Resolved merge conflicts"
       
     - Pushed the changes to the remote master branch:
       bash
       git push origin master
       

## Practice More Git Commands

For further information on Git commands and operations, refer to [Git - Book](https://git-scm.com/book/en/v6).

## Summary

This repository contains the master and new-feature branches, documenting various Git operations including setup, branching, merging, conflict resolution, and undoing commits. Each section includes the commands used and a brief description of the actions taken.

For a detailed history, refer to the commit logs and branch history in the repository.
