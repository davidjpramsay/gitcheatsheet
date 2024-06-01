# Git Cheat Sheet

## Download Latest Files

```sh
git fetch
```

```sh
git merge origin main
```

##  Create a Branch
```sh
git checkout -b new_branch_name
```

## Make a Commit

### Add all
```sh
git add .
```

### Add Single File
Use git status and tab to help indentify path.
```sh
git add dir_name/file_name
```

## Push to Remote

### Push
If first push then ```git push --up-stream origin branch_name```. Branch must match current branch.
```sh
git push
```

### Open Pull Request
github website and do shit.

## Pull a Remote Branch

### Fetch Remote References

```sh
git fetch
```
### View Remote Branches
```sh
git branch -r
```

### Check Out Branch
```sh
git checkout remote_branch_name
```

### Check Current Branch
```sh
git branch
```