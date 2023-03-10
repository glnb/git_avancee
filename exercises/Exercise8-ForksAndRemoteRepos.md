# Advanced Git
## Exercise Eight - Forks And Remote Repos

### Overview
In this exercise, we'll try creating our own Github fork of the `advanced-git-exercises` repo that we've been working with. Then we'll rename the remotes and try using `git pull --rebase` to do a cleaner pull without adding merge commits.

```
$> git checkout master
Switched to branch 'master'
```

### Exercise:
1. Create your own Github fork of `https://github.com/nnja/advanced-git-exercises`.
2. Look at your git remotes. Rename your `origin` remote (nnja's copy) to `upstream`. Add your personal fork as the `origin` remote.
3. Nina will make a change to her copy of the repo. Make a different change to your local repo, then use `git pull --rebase` to merge them.
