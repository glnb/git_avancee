# Advanced Git
## Exercise Two - Staging and Stashing

### Overview
In this exercise, we'll take a quick look at interactive staging, unstaging files, and stashing uncommitted changes.

```
$> git clone git@github.com/glnb/git_avancee.git
Cloning ...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
Checking connectivity... done.

$> cd git_avancee 

$> git checkout exercise2
Switched to branch 'exercise2'
```

### Exercise
1. Use `git ls-files -s` to view the contents of the staging area.
2. Make a change and try to stage it interactively (`git add -p`).
3. Use `git reset` to undo the staging of your file.
4. Stash your change with a unique stash message, then unstash and apply it back to the `exercise2` branch.
