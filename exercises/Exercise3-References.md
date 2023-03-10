# Advanced Git
## Exercise Three - References

### Overview
In this exercise, we'll take a look at our references (`refs`) and create some lightweight and annotated tags. Then we'll make a dangling commit from a "detached HEAD" state and learn why this isn't a great idea.

```
$> git checkout exercise3
Switched to branch 'exercise3'
```

### Exercise
1. Check the value of your `HEAD` variable (hint: look in `.git`) and confirm you're pointed at the `exercise3` branch.
2. Use `show-ref` to look at your other heads.
3. Create a lightweight tag and confirm that it's pointing at the right commit.
4. Create an annotated tag, and use `git show` to see more information about it.
5. Get into a "detached HEAD" state by checking out a specific commit, then confirm that your HEAD is pointing at this commit rather than at a branch.
6. Make a new commit, then switch branches to confirm that you're leaving a commit behind.
