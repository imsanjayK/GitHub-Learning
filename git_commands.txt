F:\MyDevEnv\gitlearn
git init // initialize a .git folder that holds information of github repository.
F:\MyDevEnv\gitlearn (master)

git remote add origin "githubPath"  // link github repository to local repository.

F:\MyDevEnv\gitlearn (master)
>git remote add origin "https://github.com/imsanjayK/git-Learning.git"

git status // check the changes made in the project.
F:\MyDevEnv\gitlearn (master)
> git   status

git add fileName.type // include changed file to local repository, this will stage file.
F:\MyDevEnv\gitlearn (master)
> git add git_commands.txt

> git add -A // stage all new and changed file to git

git commit -m "git_commands - Sanjay" // commit changes
F:\MyDevEnv\gitlearn (master)
>git commit -m "git_commands - Sanjay"

F:\MyDevEnv\gitlearn (master)
>git commit -a -m "git add all - Sanjay" // commit all changes

git log  // log of changes 
F:\MyDevEnv\gitlearn (master)
>git log
commit 9adc42f452e7be0f1457a8198382bd002d5ecae0 (HEAD -> master)
Author: c0demark <kumarvijay336@gmail.com>
Date:   Sat Jun 29 22:59:28 2019 +0530

    commit all - Sanjay

git branch branchName	
F:\MyDevEnv\gitlearn (master) // create branch
>git branch firstbranch

git checkout branchName // switch between branch and master 
F:\MyDevEnv\gitlearn (master)
>git checkout firstbranch
Switched to branch 'firstbranch'

git merge branchName // combining branches
F:\MyDevEnv\gitlearn (master)
>git merge firstbranch

git rebase branchName // same as merge
F:\MyDevEnv\gitlearn (firstbranch)
? git rebase master
Current branch firstbranch is up to date.

F:\MyDevEnv\gitlearn (master)
git push origin master

F:\MyDevEnv\gitlearn (firstbranch)
λ git push origin firstbranch