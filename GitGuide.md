# Git Guide

## Guides

### Update `dev ` branch
The `dev ` branch represents the latest state of the project. All latest features/ fixes by everyone in the team will be merged into the `dev` branch.
1. Go to your dev branch
```
git checkout dev
```
2. Pull updated dev branch from origin
```
git pull origin dev
```

### Create a new branch for new task
When creating a new branch, always checkout from the `dev` branch to ensure that you have the same code as everyone else.
1. Go to your `dev` branch
```
git checkout dev
```
2. (Optional) If there are new commits merged to `dev`. It it better to update your local copy of the `dev` branch to avoid conflicts.
```
git pull origin dev
```
3. Create your new branch
```
git checkout -b feature/new-feature
```

## Reference

### Change Branches
Syntax:
`git checkout <branch-prefix>/<branch-name>`
Example:
`git checkout feature/pricing`

### Create new branch
Syntax:
`git checkout -b <branch-prefix>/<branch-name>`
Example:
`git checkout -b feature/fix-footer`

### Pull updates
Syntax:
`git pull origin <branch-to-pull>`
Example
`git pull origin dev`

### Delete branch
Syntax:
`git branch -D <branch-name>`
Example:
`git branch -D feature/change-font`
