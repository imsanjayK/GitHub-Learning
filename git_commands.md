# Git Commands
## Git Init:
Initialize a .git folder that holds information of github repository.
```bash
F:\MyDevEnv\gitlearn
git init
F:\MyDevEnv\gitlearn (master)
```

## Git Remote:
Links github repository to local repository.
git remote add origin <githubPath>.
```bash
git remote add origin https://github.com/imsanjayK/git-Learning.git
```

## Git Status:
Check the changes made in the project.
```bash
git status
```

## Git Add 
Stage changed file to local repository. 
```bash
F:\MyDevEnv\gitlearn (master)
git add git_commands.txt
```
To Stage all file at onces.
```bash
git add -A or .
```

## Git Commit
Used to save changes to the local repository
Commit a particular file changes.
```bash
F:\MyDevEnv\gitlearn (master)
git commit -m "git_commands - change msg"
```
Commit all changes.
```bash
F:\MyDevEnv\gitlearn (master)
git commit -a -m "git add all - change msg"
```

## Git Logs
View log of commits made.
```bash 
F:\MyDevEnv\gitlearn (master)
git log
commit 041982412ed01e2541085991d75b8621549c3844
Author: SANJAY KUMAR <43964213+imsanjayK@users.noreply.github.com>
Date:   Sat Apr 11 19:53:46 2020 +0530
    new
```

## Git Branch 
Create new branches.
```bash	
F:\MyDevEnv\gitlearn (master)
git branch firstbranch
F:\MyDevEnv\gitlearn (firstbranch)
```

## Git Checkout 
Switch between branch and master.
```bash 
F:\MyDevEnv\gitlearn (master)
git checkout firstbranch
F:\MyDevEnv\gitlearn (firstbranch)
```

## Git Merge 
Combining branches.
```bash
F:\MyDevEnv\gitlearn (master)
git merge firstbranch
```

## Git Rebase
Works same as merge.
```bash
F:\MyDevEnv\gitlearn (firstbranch)
git rebase master
Current branch firstbranch is up to date.
```

## Git Push
Update Git repository from local.
```bash
F:\MyDevEnv\gitlearn (master)
git push
F:\MyDevEnv\gitlearn (firstbranch)
git push origin firstbranch
```

## Git Pull
Get update work from Git repository to local.
```bash
F:\MyDevEnv\gitlearn (master)
git pull
Already up-to-date.
```