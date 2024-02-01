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

