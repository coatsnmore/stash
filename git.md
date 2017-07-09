[Oh shit, git!](http://ohshitgit.com/)

### configuring proxy

*can replace global/local*

  ```git config --add --global http.proxy http://localhost:3128```
  ```git config --add --global https.proxy http://localhost:3128```

  ```git config --unset --global http.proxy```
  ```git config --unset --global https.proxy```

### branching

  ```Git branch topic1```
  ```Git checkout topic1```
  ```Git add -A```
  ```Git commit -m “descriptive comment about what was changed”```
  ```git push --set-upstream origin topic1```
  ```Git push```