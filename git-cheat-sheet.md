# Links

[Oh shit, git! (external website)](http://ohshitgit.com/)
[git mergetool](https://gist.github.com/karenyyng/f19ff75c60f18b4b8149)
[merge conflicts](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/merge-conflicts)
[git reset](https://git-scm.com/blog)

# Configuring Proxies

*can replace global with local*

### Add

  `git config --add --global http.proxy http://localhost:3128`

  `git config --add --global https.proxy http://localhost:3128`

### Remove

  `git config --unset --global http.proxy`

  `git config --unset --global https.proxy`
  
# Refresh Brancehs

  `git remote update origin --prune`

# Branching

Stash any current uncommitted changes that you want to keep.

  `git stash`

Create a branch.

  `git branch topic1`

Checkout the branch.

  `git checkout topic1`

Add all the files with `-A` or `git add [specific file]`.

  `git add -A`

Commit to local branch.

  `git commit -m “descriptive comment about what was changed”`

Points your client to the correct remote branch.

  `git push --set-upstream origin topic1`

Push the changes to remote branch in the repo.

  `git push`
