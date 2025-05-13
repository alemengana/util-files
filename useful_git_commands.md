### 🔀 Fetch changes from your current branch and then update your current branch with changes coming from another branch(in this case from origin)

```sh
git fetch && git rebase origin/<branch_name>
```

### 🔀 If your excess commits are only visible to you, you can just you can use git reset to move back to where the origin is. Next command will reset the state of the repository to the previous commit, and it will discard all local changes.

```sh
git reset --hard origin/<branch_name>
```

### 🔀 And locally, if you commit your changes and not pushed

```sh
git reset --hard <branch_name>
```