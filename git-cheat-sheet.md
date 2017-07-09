# Links

[Oh shit, git! (external website)](http://ohshitgit.com/)

# Configuring Proxies

*can replace global with local*

### Add

  `git config --add --global http.proxy http://localhost:3128`

  `git config --add --global https.proxy http://localhost:3128`

### Remove

  `git config --unset --global http.proxy`

  `git config --unset --global https.proxy`

#  Branching

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