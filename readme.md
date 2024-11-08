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
