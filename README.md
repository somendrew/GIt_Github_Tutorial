# Git and Github


## Commands

### SETUP:
git config --global user.name “[firstname lastname]”
git config --global user.email “[valid-email]”

## SETUP & INIT
git init

 retrieve an entire repository from a hosted location via URL
###git clone [url]

## STAGE & SNAPSHOT

### git status
show modified files in working directory, staged for your next commit

### git log
to check the log 

### git add [file]
add a file as it looks now to your next commit (stage)

### git reset [file]
unstage a file while retaining the changes in working directory

### git diff
diff of what is changed but not staged

### git diff --staged
diff of what is staged but not yet commited

### git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot

### git branch 
to check branch

### git commit -m "[message]"
to commit a file and add message

### git push origin [branch]
push the file on github

### git remote origin [link]
to work with the link

## Temporary commit

### git stash
Save modified and staged changes

### git stash list
list stack-order of stashed file changes

### git stash pop
write working from top of stash stack

### git stash drop
discard the changes from top of stash stack


### git rebase -i [paste]
merge commits

### create a new branch
git branch [name]


