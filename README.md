# Git and Github

## Global Configuration
```
git config ---global user.name "name"
git config --global user.email "email@gmail.com"
git config -global core.editor "code --wait"
git config --global core.autocrlf
```

##  Initialize git
When you initialize a resource, a .git file is created. It is not visible. It is a hidden folder. 
```code

git init

```
You can hit following command to see the hidden folders:
1. If you are in window and in CMD:  dir /a
2. If are in window but in powershell :  ls -Force

## Adding File : 
```
git add .
git add filename
git commit -m “Message is here”
```

## Pushing to github
1. Make a repository on github
2. Copy the repo URL
```

Git remote add origin url__here

```
afte that use the command below to push to github
```

git push origin main

```
## Unstage
```

git restore –staged filename.txt

```
## History of commits : 
```

git log

```
## Removing commits : 
Copy the hash value till where you want project to restore where it was: 
```

git reset hash_value

```

## Stashing
```
git stash
git stash pop
```

## Branching
```
git branch
git checkout main
git merge branch_name
```
