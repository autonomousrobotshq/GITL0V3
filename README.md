# GIT Magic

## Git basics

### basic commands
    git status

    git clone [REPO] [LOCAL FOLDER]
    
    git pull

    git push

    git push -f
    
    git commit -m [COMMIT MSG]
    
    git fetch

    git diff [OTHER BRANCH]
    
    git diff [OTHER BRANCH] [FILENAME/FOLDER]
    
    git diff [FILENAME/FOLDER]

    git log
    
    git reset
    
    git reset --soft HEAD^1
    
    git reset --hard
    
    git commit --amend
    
    git mv [OLD FOLDER] [NEW FOLDER]
    
    git rm -r [FOLDER]
    
    git rm -r --cached [FOLDER]

    git remote add [NAME] [REPO URL]
    
    git remote show
    
    git remote remove [NAME]
    
### advanced commands 
    git log --graph --decorate --pretty=oneline --abbrev-commit

## Branches

### basic commands
    git branch [NEW BRANCHNAME]
    
    git checkout [BRANCHNAME]
    
    git checkout [BRANCHNAME] [FILENAME]
    
    git switch -c [NEW BRANCHNAME]
    
    git switch [EXISTING BRANCHNAME]
    
    git branch -d [EXISTING BRANCHNAME]
    
    git branch -D [EXISTING UNMERGED BRANCHNAME]

    git push origin --delete [REMOTE BRANCH NAME]
    
    git stash
    
    git stash pop

## Rebasing

### basic commands
    git rebase -i [CHECKSUM]
    
    git rebase -i HEAD~[NUMBER OF COMMITS]
    
    git rebase --continue
    
    git rebase --abort

## Gitmodules

### basic commands
    git submodule add [REPO] [LOCAL FOLDER]
    
    git submodule init
    
    git submodule --update --recursive
    
    git sync
    
    git submodule set-url [MODULE FOLDER] [NEW REPO]
    
    git mv [OLD FOLDER] [NEW FOLDER]

## Pull Requests

## Continuous-Integration

## Tagging

## Packaging