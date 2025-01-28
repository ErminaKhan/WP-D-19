
# Git Commands for Cloning and Pushing

A breakdown of the basic Git commands to clone and push code.


## Cloning a Repository

To clone a remote repository to your local machine, use the following command:

```
git clone <repository_url>
```
Explanation:

1. "git clone" downloads the entire repository (with all files, branches, and history) from a remote server to your local computer.

2. Replace <repository_url> with the actual URL of the repository you want to clone (e.g., https://github.com/user/repository.git).
## Staging Changes

Before committing your changes, you need to add files to the staging area:

```
git add <file_name>       # To add a specific file
git add .                 # To add all modified files in the current directory
```

Explanation:

1. "git add" stages your changes, telling Git to include them in the next commit.
2. If you want to add all modified or new files, use "git add ." (dot means current directory).
## Committing Changes

After staging your files, commit them to save the changes in your local repository:

```
git commit -m "Your commit message"
```
Explanation:

1. "git commit" creates a snapshot of your changes and stores them in the repository history.
## Pushing Changes to Remote Repository

Once you've committed your changes, push them to the remote repository to sync your work with others:

```
git push origin <branch_name>
```

Explanation:

1. "git push" uploads your commits from your local repository to a remote repository (like GitHub).