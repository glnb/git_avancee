# Advanced Git
## Exercise Ten - Hooks

### Overview
In this exercise, we'll set up a pre-commit hook and see how this powerful tool might be used to keep low-quality code from getting into your repo.

```
$> git checkout exercise10
Switched to branch 'exercise10'
```

Note: This pre-commit hook script will only work in a Bash environment. Windows users can follow along but the script my not work as expected.

### Exercise
1. Copy the `pre-commit` script into your git hooks folder and make it executable. Try committing a shell (.sh) script to your repo with no shebang (#!) line at the top - your commit should fail. Try committing a script with a shebang line - your commit should succeed.
