# Git Commands

Initialise as git directory:

> git init

Move files from work area to staging:

> git add . (add all)
> git add [file.name]

Check commit status:

> git status

Move staged to local repo:

> git commit -m "Message"

Link remote repo:

> git remote add [ssh link]

Local -> Remote:

> git push -u origin main
> git push (if tracked)
> git push origin [branch]

Copy remote to local:

> git clone [link]

Get all changes from remote repo to working directory:

> git pull origin [branch] (git merge + git push)
