# Advanced Git
## Exercise Six - Fixing Mistakes

### Overview
In this exercise, we'll practice reverting a file and cleaning our repo. Then we'll take a deeper look at `git reset` and `git revert` to go back in time.

```
$> git checkout exercise6
Switched to a new branch 'exercise6'
```

### Exercise
1. Make bad changes to a file, then use `git checkout` to fix it. Use `git checkout` to reset your file back to an earlier point in time.
2. Use `git clean` to remove untracked files from your repo. Remember to use `--dry-run` first.
3. Stage a change and then use `git reset` to unstage it. Use `git reset --hard` to reset your branch back pointer, staging area, and working area to an earlier commit. Use "mixed mode" to reset your branch back to an earlier commit, then use `ORIG_HEAD` to reset your branch back to where you were.
4. Practice using `git revert` to safely revert a commit with a new commit.
