# Advanced Git
## Exercise One - Under The Hood of a Simple Commit

### Overview
In this exercise, we'll create a simple commit, and then peek under the hood at the objects stored in our `.git` folder to gain some insight into how things work.

### Prerequisite
If you have a Mac with `brew` set up, install `tree`. This makes it easy to visualize the contents of your `.git` folder.

### Exercise
1. Create a new folder and initialize it as a git repo
2. Create a file, stage it, and commit it to your new repo
3. Look at your `.git` folder, using `tree` if you have it
4. Inspect the objects in your `.git/objects` folder using `git cat-file`. See if you can find the tree, blob, and commit objects for your recent commit.
5. Look at your `.git/HEAD` and `.git/refs/heads/master` files and see if you can figure out where these references are pointing to.
