# Git Cheat Sheet

## Download Latest Files

```zsh
git fetch
```

```zsh
git merge origin main
```

##  Create a Branch
```zsh
git checkout -b new_branch_name
```

## Make a Commit

### Add all
```zsh
git add .
```

### Add Single File
Use git status and tab to help indentify path.
```zsh
git add dir_name/file_name
```

## Push to Remote

### Push
If first push then ```git push --up-stream origin branch_name```. Branch must match current branch.
```zsh
git push
```

### Open Pull Request
```zsh

```

## Pull a Remote Branch

### Fetch Remote References

```zsh
git fetch
```
### View Remote Branches
```zsh
git branch -r
```

### Check Out Branch
```zsh
git checkout remote_branch_name
```

### Check Current Branch
```zsh
git branch
```