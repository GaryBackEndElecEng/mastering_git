### https://www.youtube.com/watch?v=S7XpTAnSDL4

## hello GIT

- track files:=> git add filename
- git log ## gives you the history of the author,data of all tracking

```GIT
commit 6f247f1d4da3d0d98483cfb5808ed3b0bcbbc045 (HEAD -> main)
Author: gary2 <garyatgreatvacations4u@gmail.com>
Date:   Mon Apr 28 11:06:03 2025 -0400

     add hello and test files

commit 2809e66ec4195238501ca617731c10a7c65e1490
Author: gary2 <garyatgreatvacations4u@gmail.com>
Date:   Mon Apr 28 11:03:11 2025 -0400
```

## restore project to previous version

- copy the commit hash of what you want to go too
- then git checkout "commit hash"; sh as
- git checkout 2809e66ec4195238501ca617731c10a7c65e1490

## to go back to the current state, you checkout your branch

git checkout main or git checkout -f main

## change master branch

- git branch -M main

## ADD ORIGN TO PROJECT

- git remote add origin "the link from github"
- git remote add origin https://github.com/masterconnect-wallace/masteringGit.git

### PUSH UPDATES TO origin

- git push -u origin main

## REMOVE ORIGIN

-git remote remove origin;

## adding new origin:

git remote add origin https://github.com/masterconnect-wallace/mastering_git.git;

## whe you change origin ( remove and then add) you have to pull the repo to your main to sync it

## FOR UNLINE HELP TYPE git help [action name], such as 'push' 'config',,,,

## branches are used to work on a section of the code that does not affect the main branch; you do git branch 'a new branch name'. this create a branch that un effects the main branch until you merge the work.

```GIT
PS C:\Users\garya\projects\vue\gitpractice\mastering> git branch
  branch-name ;=> new branch //OR git checkout -b 'new-branch name'
* main

PS C:\Users\garya\projects\vue\gitpractice\mastering> git branch
  branch-name
  main
* new-branch
```

## to switch to the new branch :=> git checkout branch-name and it will enter you into that branch name.

```GIT
PS C:\Users\garya\projects\vue\gitpractice\mastering> git checkout branch-name
Switched to branch 'branch-name'

PS C:\Users\garya\projects\vue\gitpractice\mastering> git checkout -b new-branch
Switched to a new branch 'new-branch'
```

## to go back to main :=> git checkout main => this will bring you back to main

```GIT
PS C:\Users\garya\projects\vue\gitpractice\mastering> git checkout main
Switched to branch 'main'
```
