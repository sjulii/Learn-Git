## 10 Advanced Git Commands

1. change last commit message

```
$ git commit --amend -m "initial"
```

2. Undoing Your Last Commit (That Has Not Been Pushed)

```
$ git reset --soft HEAD~
```

Add a number to the end to undo multiple commits. For example, to undo the last 2 commits (assuming both have not been pushed)

```
$ git reset --soft HEAD~2
```
