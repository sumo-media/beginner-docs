
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

###  Finishing a branch/ task
Once you are done for the branch or task. You have to push the codes to the remote repository (Github/ Bitbucket) so the project maintainer can review and merge your branch to the `dev` branch.
1. Make sure you have commited all your changes. First add your changes to staging.
```
git add .
```
2. Commit your changes. As much as possible make your commit message clear and describes the changes in a brief way.
```
git commit -m "<your commit message/ description here>"
```
3. Push your branch to the remote repository
```
git push origin <branch-prefix>/<branch-name>
```
4. Lastly create a pull request.

## Reference

### Change Branches
Syntax:
```
git checkout <branch-prefix>/<branch-name>
```
Example:
```
git checkout feature/pricing
```

### Create new branch
Syntax:
```
git checkout -b <branch-prefix>/<branch-name>
```
Example:
```
git checkout -b feature/fix-footer
```

### Pull updates
Syntax:
```
git pull origin <branch-to-pull>
```
Example
```
git pull origin dev
```

### Delete branch
Syntax:
```
git branch -D <branch-name>
```
Example:
```
git branch -D feature/change-font
```
