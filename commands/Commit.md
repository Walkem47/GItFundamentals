# git commit

THe command `git commit` will take all tracked changes (items added with [git add](./ADD.md)) and package them up in what is called a commit.

Commits come with commit messages that are required for  each commit. You add a message to a commit command by using the `-m` flag followed by a message in quotes. 

A commit message _can_ be anthing but best  practice dictates taht you should  use that message to indicate the changes included in the commit. 

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:

```
git add .
git commit -m "Added rigister functionality"
```

THen when viewing history of a git repository, you can pinpoint where the registration functionality was added.

## Resources

- [Git Commit Documentation](https://git-scm/docs/git-commit)

---

[Back to home](../README.md)
