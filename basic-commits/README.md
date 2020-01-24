# Git Kata: Basic Commits
This kata will introduce you to the `git add` and `git commit` commands.

This is a very introductory kata. if you have used `git status`, `git log --oneline --graph`, `git add` and `git commit` extensively you should probably skip it.

You can look at the bottom of this file, if you have not yet done basic git configuration.

## The task


2. What does `git log` look like?

fatal: your current branch 'master' does not have any commits yet

4. What does the output from `git status` look like now?

atakei@annas-mbp exercise % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    newfile.txt

nothing added to commit but untracked files present (use "git add" to track)

6. How does `git status` look now?

atakei@annas-mbp exercise % git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
    new file:   newfile.txt

8. How does `git status` look now?

atakei@annas-mbp exercise % git status
On branch master
nothing to commit, working tree clean

10. What does `git status` look like now?

atakei@annas-mbp exercise % git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
    modified:   newfile.txt

no changes added to commit (use "git add" and/or "git commit -a")

12. What does `git status` look like now?

atakei@annas-mbp exercise % git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
    modified:   newfile.txt

15. What does the `status` look like now? The `log`?

atakei@annas-mbp exercise % git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
    modified:   newfile.txt

no changes added to commit (use "git add" and/or "git commit -a")

atakei@annas-mbp exercise % git log
commit 1c3d470443130170975446933d963a088042c5ff (HEAD -> master)
Author: Anna Takei <atakei@annas-mbp.lan>
Date:   Fri Jan 24 14:41:36 2020 -0800

    Commit modified newfile.txt

commit c4735b6c52bc9c0f4da1686721dbc0f445eeb068
Author: Anna Takei <atakei@annas-mbp.lan>
Date:   Fri Jan 24 14:38:16 2020 -0800

    Commit newfile.txt
