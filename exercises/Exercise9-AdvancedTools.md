# Advanced Git
## Exercise Nine - Advanced Tools

### Overview
In this exercise, we'll take a look at some of the advanced features of `git grep`, we'll learn how to "cherry-pick" commits, then we'll take a look at `git blame` and `git bisect`.

```
$> git checkout exercise9
Switched to branch 'exercise9'
```

### Exercise
1. Use `git grep` to search for a string in your git repo. Try using arguments for `git grep` to print line numbers and group results by file. Use the `--cached` option to see the difference between grepping your working area and your staging area.
2. Try to cherry-pick a commit from one branch into the `exercise9` branch.
3. Use `git blame` to see who touched a file. Delete a file and commit your change. Use `git blame` again to blame a file from an earlier point in time, before it was deleted.
4. Start a `git bisect` session and try to find which commit introduced the word "emergency" into `hello.txt` 
