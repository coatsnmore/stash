Git Cheat Sheet
====
* [Configuring Proxies](#configuring-proxies)
* [Refreshing Remote Branches Locally](#refresh-branches)
* [Branching commands](#branching)
* [External Links](#links)

# Configuring Proxies

You can set configuration values to different scopes.  For example, I tend to set my proxy configuration globally to act as a default configuration for any workspace.

Scopes include:
* `--local` *(default)*
* `--global`
* `--system`

### Add

```bash
git config --add --global http.proxy http://localhost:3128
git config --add --global https.proxy http://localhost:3128
```

### Remove

```bash
git config --unset --global http.proxy`
git config --unset --global https.proxy`
```
  
# Refresh Branches

```bash
git remote update origin --prune
```

# Branching

Stash any current uncommitted changes that you want to keep.

```bash
git stash
```

Create a branch.

```bash
git branch topic1
```

Checkout the branch.

```bash
git checkout topic1
```

Add all the files with `-A` or `git add [specific file]`.

```bash
git add -A
```

Commit to local branch.

```bash
git commit -m “descriptive comment about what was changed”
```

Points your client to the correct remote branch.

```bash
git push --set-upstream origin topic1
```

Push the changes to remote branch in the repo.

```bash
git push
```

# Links

* [Oh shit, git! (external website)](http://ohshitgit.com/)
* [git mergetool](https://gist.github.com/karenyyng/f19ff75c60f18b4b8149)
* [merge conflicts](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/merge-conflicts)
* [git reset](https://git-scm.com/blog)