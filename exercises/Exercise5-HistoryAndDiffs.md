# Advanced Git
## Exercise Five - History and Diffs

### Overview
In this exercise, we'll practice making a good commit, take a look at some of the interesting command line arguments for `git log`, use `git show` to get more information about a commit, then take a quick look at `git branch`.

```
$> git checkout exercise5
Switched to a new branch 'exercise5'
```

### Exercise
1. Practice creating a well-crafted commit - look at the format given on the slides for help.
2. Use `git log` to find commits created since yesterday. Rename a file and use the `--name-status` and `--follow` options to `git log` to track down when the file was renamed, and what it used to be called. Use `--grep` to search within commit messages, and `--diff-filter` to find renamed and modified files from `git log`.
3. Use `git show` to get more information about a specific git hash.
4. Try the `--merged` and `--no-merged` options to `git branch` to see which branches have been merged into `master` (or not).
