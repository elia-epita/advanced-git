# Advanced Git
## Exercise Seven - Rebase and Amend

### Overview
In this exercise, we'll practice amending commits, then we'll try a normal rebase and an interactive rebase.

### Prerequisite 
You should have the [`advanced-git-exercises`](https://github.com/elia-epita/advanced-git-exercises)  repository cloned locally. Checkout the `exercise7` branch:

```
$> git checkout exercise7
Switched to a new branch 'exercise7'
```

### Exercise
1. Make a commit, then practice using the `--amend` option to make another change to the previous commit.
2. Make two non-conflicting changes to two different branches. Rebase one branch onto the other.
3. Make another change to your current branch. Use an interactive rebase (`git rebase -i`) to rebase the two branches. Try squashing your two commits and rewording the message during the rebase.

#### End of Exercise Seven