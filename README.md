# SquashCommits 
## Squash the Last X Commits ##

first check your log
```git log```

git rebase -i HEAD~[X]

```git rebase -i HEAD~4```

OR
open rebase window using SHA value

```git rebase -i <first 7 alphanumeric of SHA>```

Git will start the system default editor (the Vim editor)

Follow the instruction given in rebase interactive window and make the changes accordingly.

**TO SAVE**
press esc key

type :x!

press return key

write your final commit message

press esc again

type :wq! or :x!

press return key

**PUSH (if all these extra commits were pushed in GitHub repo also)
you have to push changes forcefully.
**

```git push -f origin master```

replace ‘origin’ with your remote name and ‘master’ with your branch name.

Squash all your commits
