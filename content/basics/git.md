# Git
Git is a version control system for software development. 

When working with others or on your own projects, version control is vital. Multiple features may be in
 development concurrently, and version controls allows code isolation and merging. 
 
## Useful Links
[Git documentation](https://git-scm.com/docs)

[Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials/what-is-git)

## Basics

### Initialize a Git repository
```git init <directory>```

or from within directory

```git init```

### Clone a repository
```git clone <repo>```

### Stage item(s) for a commit
```git add <directory>```

```git add <file>```

```git add -A``` (all items available in directory)

```git add -u``` (updated files already tracked)

### Commit staged changes with a message
```git commit -m <message>```

### Create a new branch
```git branch <branch name>```

```git branch -b <branch name>``` (create and switch to it)

### View all branches
```git branch```

### Switch to a branch
```git checkout <branch name>```

### Push to remote
```git push -u origin <branch name>```