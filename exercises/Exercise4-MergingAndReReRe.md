# Advanced Git
## Exercise Four - Merging and ReReRe

### Overview
In this exercise, we'll take a look at the fast-forward merge, learn how to make a non-fast-forward merge, then learn how to use git's Reuse Recorded Resolution (ReReRe) functionality to automate complex merges.

```
$> git checkout exercise4
Switched to branch 'exercise4'
```

### Exercise
1. Merge the `exercise3` branch into `exercise4`, and look at the git log.
2. Use `git reset --hard HEAD^` to reset your `exercise4` branch back one commit, then use the `--no-ff` option to `git merge` to merge `exercise3` again. Look at the git log, how is it different from the last step?
3. Make two conflicting changes to `hello.txt` in two different branches.
4. Enable ReReRe, then merge one branch into the other.
5. Backup again with `git reset --hard HEAD^`, then attempt the merge again. Notice how ReReRe automatically resolves the conflict for you.
