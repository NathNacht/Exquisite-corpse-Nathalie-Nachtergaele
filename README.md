# Git Cheat Sheet

The Ultimate Git Cheat Sheet

![Github](/images/github.png)

## Configuration

```bash
# Set User Name and Email
$ git config --global user.name "Your Name"
$ git config --global user.email "your.email@example.com"

# View Configuration
$ git config --list
```

## Basic Commands


A new repository can either be created **locally**, or an **existing repository** can be cloned. When a repository was initialized locally, you have to push it to GitHub afterwards.

```bash
# Initialize a Repository

$ git init

# Clone a Repository (with all of the files, branches and commits)
$ git clone <repository-url>

# Stage Changes
$ git add <file(s)>

# Commit Changes
$ git commit -m "Your commit message"
```

The git init command turns an existing directory into a new Git repository inside the folder you are running this command. After using the git init command, link the local repository to an empty GitHub repository using the following command:

```bash
$ git remote add origin [url]
```

## Branches

```bash
# Create a New Branch
$ git branch <branch-name>

# Show all Branches
$ git branch -r

# Switch to a Branch
$ git checkout <branch-name>
# OR
$ git switch <branch-name>

# Create and Switch to a New Branch
$ git checkout -b <new-branch-name>
# OR
$ git switch -c <new-branch-name>

# Merge Branch
$ git merge <branch-name>

# Delete a Branch
$ git branch -d <branch-name>
```

## Remote Repositories

```bash
# Add a Remote
$ git remote add <remote-name> <remote-url>

# Fetch Changes
$ git fetch <remote-name>

# Pull Changes (Fetch from and integrate with another repository or a local branch)
$ git pull <remote-name> <branch-name>

# Push Changes
$ git push <remote-name> <branch-name>
```

![git pull force](/images/gitpullforce.jpg)
![git push force](/images/gitpushforce.jpg)


## Undo Changes

```bash
# Discard Unstaged Changes
$ git checkout -- <file(s)>

# Unstage Changes
$ git reset <file(s)>

# Amend the Last Commit
$ git commit --amend

# Revert a Commit
$ git revert <commit-hash>

# Reset to a Specific Commit
$ git reset --hard <commit-hash>
```
![git reset hard](/images/gitresethard.jpg)
![git revert](/images/gitrevert.jpg)



## View Changes

```bash
# View Unstaged Changes
$ git diff

# View Staged Changes
$ git diff --staged

# View Commit History
$ git log
```

## Tagging

```bash
# Create a Tag
$ git tag <tag-name>

# Create Annotated Tag
$ git tag -a <tag-name> -m "Tag message"

# Push Tags
$ git push --tags
```

## Miscellaneous

### The .gitignore file

Sometimes it may be a good idea to exclude files from being tracked with Git. This is typically done in a special file named .gitignore. You can find helpful templates for .gitignore files at github.com/github/gitignore.

### Other Misc

```bash
# See Git Status (Show the status of changes as untracked, modified, or staged)
$ git status

# See Git Help
$ git --help

# Display the commit history
$ git log
```
Signed by gerrit
