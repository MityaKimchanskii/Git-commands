# Git-commands

**mkdir <name>** - create folder

**ls** - check what inside current folder
**ls -a** - to see all hidden files

**cd ...** - go to parent folder

**cd <name>** - open folder

**git init** - git initialiazing

**touch <name.extension>** - create file, we can create multiple files, separete them with space

**git add .** - moves changes from the working directory to the staging area

**git add -p** - add what to commit

**git commit -m "message"** - add commit
**git commit --amend** - add changes in previous commits

**git diff** - check difference

**git log** - read all commits

**vi. gitignore** => tap "o" to start modifying => "Esc :wq" to save and quit - open gitignore file

**git push** - push all to remote rep 

**git status** - check any changes in dir

**git checkout -b <name>** - create new branch
**git checkout -D <name>** - delete branch
**git branch** - current branch
**git merge** - merge branches, integrate changes from different branches

**git pull** - Pulling is the automated version of git fetch. 
               It downloads a branch from a remote repository, 
               then immediately merges it into the current branch.

**git clone <https:....>** - create clone from remote repository (for example: GitHub)
**vi README.md** - make changes in readme file, to start press <o> then type, after <esc :wq> to save changes

**git rebase -i** - rebase and squash => ctrl v - to squash all commits that were choosen => <c> <s> => <esc esc> => x => <i> <p> <esc>

**git commit --amend --no-edit --date="Fri Aug 05 20:00:00 2022 -0600"** - add commit for past time

**git push --force** - be very carefull when using 


