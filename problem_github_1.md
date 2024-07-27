# problem & Solution #1
## Problem::

! [rejected] main -> main (fetch first) error: failed to push some refs to 'https://github.com/username/repo-name.git'

 hint: Updates were rejected because the remote contains work that you do not 

 hint: have locally. This is usually caused by another repository pushing to 

 hint: the same ref. If you want to integrate the remote changes, use 
 
 hint: 'git pull' before pushing again. 
 
 hint: See the 'Note about fast-forwards' in 'git push --help' for details.

## Solution::

```bash
git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp 
```
--solved from stack overflow (Aurelio A)