## Common Operations
1. **Git fetch:**
    Git command that downloads changes from a remote repository to your local repository, but it does not apply those changes to your working directory. Instead, it updates your local copy of the remote repository's branches and tags, allowing you to review and merge the changes later.
2. **gir merge:**
    apply the changes to your working directory
3. **git reset --hard:**
    resets your working directory and index to a specified commit, discarding any changes that have been made to tracked files in your working directory and staged changes in the index.

## Push formula
```
git add .
git commit -m "<context>"
git push
```