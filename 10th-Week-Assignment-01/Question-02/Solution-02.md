# Solution-02.

# Git Workflow

## Working Directory
The working directory is the local directory on your machine where you have your Git repository cloned. It contains all the files and directories related to your project. Modifications made in the working directory are recognized by Git, but they are not automatically included in the next commit.

## Staging Area (Index)
The staging area, also known as the index, acts as an intermediate area between the working directory and the Git repository. It allows you to selectively stage changes before committing them. This provides more control over the content of each commit.

- `git add [file]`: Stages the specified file for the next commit.
- `git add .` or `git add -A`: Stages all changes in the working directory for the next commit.

## Repository
The Git repository is the database where Git permanently stores the project's history and all changes made to the files over time. It is typically located in a hidden subfolder named `.git` within the project's root directory.

- `git commit`: Records changes staged in the index to the repository. Each commit has a unique identifier (hash) and a commit message describing the changes.
- `git log`: Displays a log of all commits in the repository, showing commit messages, authors, dates, and commit hashes.

Commits in the repository create a timeline of the project's development, enabling developers to track changes and collaborate effectively.

In summary, the Git workflow involves making changes in the working directory, staging specific changes in the index, and then committing those changes to the repository. This process provides granular control over the content of each commit and helps maintain a well-organized project history.
