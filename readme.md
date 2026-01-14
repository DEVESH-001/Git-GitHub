# We will we covering `git` and `github` in this repository

## Git [https://docs.github.com/en/get-started/git-basics]

- Git is a version control system that allows developers to track changes in their codebase over time. It enables multiple developers to collaborate on a project by managing changes and merging contributions from different sources.

- Key features of Git include:
  - Distributed version control: Each developer has a complete copy of the repository, allowing for offline work and faster operations.
  - Branching and merging: Developers can create branches to work on new features or bug fixes independently, and later merge them back into the main codebase.
  - Commit history: Git maintains a detailed history of changes, allowing developers to review and revert to previous versions if needed.
  - Collaboration: Git supports collaboration through platforms like GitHub, GitLab, and Bitbucket, enabling code sharing and team workflows.

- Git Commands:

- ls -la: List all hidden files in the current directory.
- git status: Show the current status of the repository, including changes to be committed, untracked files, and modified files.
- commit : its liks a check-point, it saves the current state of the project.
- git add one.txt: Stages the file "one.txt" for the next commit, only one.txt will be included in the commit.
- git add . : Stages all changes (new, modified, and deleted files) in
- git commit -m "Initial commit": Commits the staged changes with the message "Initial commit".
- git log: Displays the commit history of the repository, showing details such as commit hashes, authors, dates, and commit messages.
- git log --oneline: Displays a condensed version of the commit history, showing each commit on a single line with its abbreviated hash and commit message.
- git config --global user.name "Your Name": Sets the global Git configuration for the user's name.
- git config --global core.editor "code --wait" : Sets the default text editor for Git to Visual Studio Code.

## Working with Branches

- git branch: Lists all branches in the repository and indicates the current branch.
- git branch feature-branch: Creates a new branch named "feature-branch".
- git checkout feature-branch: Switches to the branch named "feature-branch".
- git checkout -b feature-branch: Creates and switches to a new branch named "feature-branch".
- git merge feature-branch: Merges the changes from "feature-branch" into the current branch.

## Git Diff & Stash

- git diff: Shows the differences between the working directory and the staging area or between two commits.
- git stash: Temporarily saves changes in the working directory that are not yet ready to be committed.
- git stash pop: Applies the most recent stashed changes and removes them from the stash list.
- git stash list: Lists all stashed changes.
- git diff --staged: Shows the differences between the staged changes and the last commit.

`-- , ++`

- -- indicates the file 1 before modification
- ++ indicates the file 1 after modification
