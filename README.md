Assignment Summary: Git Operations
This repository documents the steps taken to complete an assignment involving various Git operations. Below is a summary of the tasks completed along with relevant details:

Tasks Completed
1. Setup a Remote Repository and Initial Commit
Setup Remote Repository:
Created a new repository named Assignment-2 on GitHub.
Added a README.md file with initial content ("Hello, Git!").
Commit Changes:
Initialized Git locally with git init.
Added README.md to the staging area with git add README.md.
Committed changes to the local repository with git commit -m "Initial commit".
2. Creating and Merging a New Branch
Create a New Branch:

Created a new branch named new-feature using git checkout -b new-feature.
Made changes to README.md on the new-feature branch.
Commit and Push Changes:

Added changes (git add README.md) and committed (git commit -m "Add new feature to README").
Pushed new-feature branch to remote repository with git push origin new-feature.
Merge Branches:

Merged new-feature branch into master using a pull request on GitHub.
3. Resolving Merge Conflicts
Encountered Merge Conflict:
During merging new-feature into master, resolved conflicts in README.md.
Manually edited conflicting sections in README.md, removed conflict markers, staged (git add README.md), and committed the changes (git commit -m "Resolved merge conflicts").
Pushed the merged changes to master on the remote repository with git push origin master.
4. Handling Undo Operations
Undo Last Commit:
Used git reset HEAD^ to undo the last commit locally.
5. Verification and Final Push
Verification and Final Push:
Ensured local and remote branches (master and new-feature) were up-to-date with git status and git log.
Pushed final changes to GitHub repository using git push origin <branch>.
Additional Resources
For more details on Git commands and operations, refer to the following resources:

Git - Book
YouTube - Git Tutorial
