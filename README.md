# Git Basics

### Initialize a new Git repository:
```bash
git init
```

### Rename the current branch 
```bash
git branch -m branch_name
```

### Create and switch to a new branch:
```bash
git checkout -b new_branch_name
```

### Switch to a specific branch:
```bash
git checkout branch_name
```

### Check the status of the repository:
```bash
git status
```

### Stage changes for commit:
```bash
git add . 

# or for a specific file:
git add filename
``` 

### Commit staged changes:
```bash
git commit -m "message"
```

#### Shortcut to stage and commit changes for modified file:
```bash
git commit -am "message"
```