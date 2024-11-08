# Git Guide 2
### 1. Config user
```
git config --global user.name "Your Full Name"
git config --global user.email "15584444@fje.edu"
git config --list
```
### 2. Init git
```
mkdir "Repository Name"
cd ".\Repository Name"
git init
dir -hidden
```
### 3. First commit
```
git status
git add .\file.ext
git status
git commit -m "Commit message: brief description"
git status
git log
```
### 4. Create branch
```
git branch dir/readme/steps-4-to-6
git branch
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
