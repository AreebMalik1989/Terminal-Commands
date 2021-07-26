### Remove all local branches except master branch
git branch | grep -v "master" | xargs git branch -D
