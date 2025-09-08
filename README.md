# FA25-IS601855-Assignment-1
FA25-IS601855 Assignment 1 - GitHub Cheat Sheet

# cmd 1: Clone a repo

Downloads a remote repository from Git to your local system, including all the files and commit history.

```bash
git clone [url]
```

# cmd 2: Create a new branch

Creates a new branch in the local git repo. It includes all the files from the current branch.

```bash
git branch [branch-name]
```

# cmd 3: Add files from the local repo to staging area

```bash
git add [path-to-file]
```

# cmd 4: Commit changes in the local repo

Creates a new commit that includes the changes made to the staging area

```bash
git commit -m [comment]
```

# cmd 5: Push changes to remote

Push changes from local repo to remote. It will also create a new branch in remote.

```bash
git push --set-upstream origin [branch-name]
```

# cmd 6: Fetch changes from remote

Fetch changes from the remote. It does not update tracking branches.

```bash
git push fetch
```

# cmd 7: Pull changes from remote

Fetch changes from the remote and merges current branch with remote.

```bash
git push pull
```

# cmd 8: Merge branches

Join the specified branch into the current working branch.

```bash
git merge [branch-name]
```

# cmd 9: Check current branch

To check the current working branch

```bash
git branch -v
```

# cmd 10: Revert changes

To remove the changes added after git add 

```bash
git reset
```

## Linux commands

# cmd 11: List of files in current directory

```bash
ls -al
```

# cmd 12: Change directory
```bash
cd [path-to-directory]
```
