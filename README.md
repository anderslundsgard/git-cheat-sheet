# git-cheat-sheet

## Create branch
```
git branch [branch-name]
```

## Switch to branch
```
git checkout [branch-name]
```

## Create + Switch to branch
```
git checkout -b [branch-name]
```

## Commit to current branch
```
git add .
git commit -m "Commit comments..."
```

## Sync changes from main branch
```
git pull master
git checkout my-branch
git pull origin master
```

## Push and create remote branch
```
git push -u origin [branch-name]
```

## Change remote url
```
git remote set-url origin https://github.com/.../git-cheat-sheet.git
```

## Deep move
```
git clone --mirror <url_old_repo>
cd <name_old_repo>
git remote add new-origin <url_new_repo>
git push new-origin --mirror
```

## Stash
```
git stash
...
git stash pop
```
