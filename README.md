# GitLearning
I will use this repository as a git sandbox.

## git worktree

`git worktree` is a command that allows you to have n+1 branches or commits checked out at the same time, which can 
1. improve effiency when pivoting from one project to the next (avoiding `git stash`/`git add . && git commit -m "wip" && git switch -c hotfix/some-important-task`).
1. allow you to run multiple AI instances on the same repo without having each agent step on each others toes, so to speak.