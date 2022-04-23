# useful-commands
Useful Commands Reference 

## git commands

### Adding Only Untracked Files

```git stash && git add . && git stash pop```

### Reset to head of current branch and remove untracked files or directories

```git reset --hard HEAD --recurse-submodules && git clean -fd```
