# SquashCommits 
## Squash the Last X Commits ##

git rebase -i HEAD~[X]

```git rebase -i HEAD~4```

Git will start the system default editor (the Vim editor)

As we can see in the screenshot above, all four commits we want to squash are listed in the editor with the pick command.
There's a detailed guideline on how to control each commit and commit message in the commented lines that follow.
For example, we can change the pick command of commits into s or squash to squash them:
￼
