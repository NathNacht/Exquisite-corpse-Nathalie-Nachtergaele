# Git sheetsheet

This is my git cheatsheet 

## Creating repositories

A new repository can either be created locally, or an existing repository can be cloned. When a repository was initialized locally, you have to push it to GitHub afterwards.

```
$ git init
```

The git init command turns an existing directory into a new Git repository inside the folder you are running this command. After using the git init command, link the local repository to an empty GitHub repository using the following command:

```
$ git remote add origin [url]
```

Specifies the remote repository for your local repository. The url points to a repository on GitHub.

```
$ git clone [url]
```
Clone (download) a repository that already exists on GitHub, including all of the files, branches, and commits

## The .gitignore file

Sometimes it may be a good idea to exclude files from being tracked with Git. This is typically done in a special file named .gitignore. You can find helpful templates for .gitignore files at github.com/github/gitignore.


This is my git cheatsheet repo

## Git Cheatsheet

### 1. Create a new repository on the command line

```
echo "# Exquisite-corpse-Nathalie-Nachtergaele" >> README.md
```

### 2. Push an existing repository from the command line

```
git remote add origin
```

### 3. Clone a repository from GitHub to my local computer

```
git clone
```

### 4. Add a file to the staging area

```
git add
```

### 5. Commit a file to the repository

```
git commit -m "message"
```

### 6. Push a file to the repository

```
git push
```
=======


My repository cheat sheet

git clone: Clone a repository into a new directory.
git clone <repository_url>

git init: Initialize a new Git repository
git init


git add: Add changes in the working directory to the staging area.
git add <file>


git commit: Record changes in the repository.
git commit -m "Commit message"


git push: Update remote repository with local changes.
git push <remote> <branch>


git pull: Fetch from and integrate with another repository or a local branch.
git pull <remote> <branch>


git status: Show the status of changes as untracked, modified, or staged.
git status


git log: Display the commit history.
git log


git branch: List, create, or delete branches.
git branch
git branch <branch_name>
git branch -d <branch_name>


git checkout: Switch branches or restore working tree files.
git checkout <branch_name>
git checkout -b <new_branch_name>


git merge: Join two or more development histories together.
git merge <branch_name>


git remote: Manage set of tracked repositories.
git remote -v
git remote add <remote_name> <repository_url>


git fetch: Download objects and refs from another repository.
git fetch <remote>
