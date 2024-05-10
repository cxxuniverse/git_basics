# Git Basics

Here you will find some useful Git commands and a short description of what they are used for:

## Repository Initialization
### Initialize a new Git repository:
```bash
$ git init
```

## Branch Operations
### Rename the current branch 
```bash
$ git branch -m branch_name
```
### Create and switch to a new branch:
```bash
$ git checkout -b new_branch_name
```

### Switch to a specific branch:
```bash
$ git checkout branch_name
```

## Status Check
### Check the status of the repository:
```bash
$ git status
```

## Staging Operations
### Stage changes for commit:
```bash
$ git add . 

# or for a specific file:
$ git add filename
``` 

## Commit Operations
### Commit staged changes:
```bash
$ git commit -m "message"
```

#### Shortcut to stage and commit changes for modified file:
```bash
$ git commit -am "message"
```