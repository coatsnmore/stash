[Oh shit, git!](http://ohshitgit.com/)

### configuring proxy

*can replace globa/local*

git config --add --global http.proxy http://localhost:3128
git config --add --global https.proxy http://localhost:3128

git config --unset --global http.proxy
git config --unset --global https.proxy

### branching

Git branch topic1
Git checkout topic1
Git add -A
Git commit -m “topic 1”
Git push

git push --set-upstream origin topic1