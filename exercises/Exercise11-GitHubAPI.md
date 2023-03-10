# Advanced Git
## Final Exercise - Using the GitHub API


### Overview

In this exercise, we'll use the GitHub REST API to get information about ourselves, our repositories, and other repositories on GitHub.

**Note:** GitHub allows 60 unauthenticated requests per hour. If you hit your limit, and would like to keep exploring proceed to **Bonus Exercise 1** to learn how to create an API token. 

In these examples I'll be using `cURL`, which is a command line tool that allows you to make requests to a server from the terminal.

If your skill-set is more advanced, you can try a developer library for your language instead. There are GitHub developer libraries for many languages,  such as python, javascript, PHP, and more! [GitHub Developer Libraries](https://developer.github.com/v3/libraries/)

If you're unsure about which integration to use, try the exercises using `cURL` first.

This GitHub API has many uses, from getting simple profile and repository information to creating Issues programatically. 

### Prerequisite - Learn to make unauthenticated requests

We can use the GitHub API unauthenticated for many operations, but GitHub limits us to 60 requests an hour.

To get information about my user profile without authenticating, run:

```
curl https://api.github.com/users/glnb
```

Try it with your username and check out the results.
This corresponds to the [Users endpoint](https://developer.github.com/v3/users/).

### Exercise

Using the [GitHub API documentation](https://developer.github.com/v3/) answer the following questions:

1. How many GitHub users are you following?
2. Which of your repositories has the most stars?
3. What languages are present in your favorite repository?

Hints:

1. [Get a single user](https://developer.github.com/v3/users/#get-a-single-user)
2. [Search Repositories](https://developer.github.com/v3/search/#search-repositories). Stars are in the `stargazer_count`, pass in `stars` as the `sort` parameter. 
3. [List languages for a Repository](https://developer.github.com/v3/repos/#list-languages)
