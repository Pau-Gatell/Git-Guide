# Git Guide
### 1. Config user'
```
git config --global user.name "Your Full Name"
git config --global user.email "455837.clot@fje.edu"
git config --list
```

### 2. init git
```
mkdir "Git Guide"
cd ".\Git Guide"
git init
dir -hidden
```

### 3. init git
```
git status
git add .\file.ext
git status
git commit -m "Commit message: brief description"
git status
```

### 4. Create branch
```
git branch dir/readme/steps-4-to-6
```

### 5. Checkout branch
```
git checkout dir/readme/steps-4-to-6
git status
```

### 6. Merge to master
```
git checkout master
git status
git merge dir/readme/steps-4-to-6
git status
git log
```
### 7. Create Stash
```
git status
git stash
git status
```
### 8. Apply Stash list
```
git stash list
git stash apply
git status
```
### 9. Drop Stash
```
git stash list
git stash drop 1
git stash list
```
### 10. Pop Stash
```
git stash list
git stach pop
git stash list
```
### 11. Revert Commit
``` 
git log --oneline
git revert [COMMIT_ID]
```

### 12. Cherry Pick  
```
git log --oneline
git cherry-pick [COMMIT_ID]
```