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

## Merge Operations
### Merge another branch into the current branch:
```bash
$ git merge <other_branch>
```

### Merge the current branch into another branch:
```bash
$ git checkout <target_branch>
$ git merge <current_branch>
```

### Merge a specific branch into another branch:
```bash
$ git merge <source_branch> <target_branch>
```

## Reset Operations

### Reset staged changes to the state of the last commit:
```bash
$ git reset
# local changes in working directory remain intact.
```

### Reset the staged changes and move the HEAD pointer to the previous commit:

"Uncommit" the last commit ('HEAD~1 refers to the commit before the current one').

```bash
$ git reset HEAD~1
# local changes in working directory remain intact.
```

### Reset both staged and working directory changes to the previous commit:

```bash
$ git reset --hard HEAD~1
# this command will delete any changes made to the working directory (i.e. local files) !
```