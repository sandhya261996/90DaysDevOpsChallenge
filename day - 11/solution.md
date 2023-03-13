Hi 👋there,

Now we are on the Day 11 task

Advance Git & GitHub**(Git Stash,Cherry-pick,Resolving Conflicts)**

Checkout the below link for Day 12 task:

https://github.com/LondheShubham153/90DaysOfDevOps/blob/master/2023/day11/tasks.md

Git Stash:

Git stash is a command that allows you to temporarily save changes you have made in your working directory, without committing them. This is useful when you need to switch to a different branch to work on something else, but you don’t want to commit the changes you’ve made in your current branch yet.

To use Git stash, you first create a new branch and make some changes to it. Then you can use the command git stash to save those changes. This will remove the changes from your working directory and record them in a new stash. You can apply these changes later. git stash list command shows the list of stashed changes.

You can also use git stash drop to delete a stash and git stash clear to delete all the stashes.

Cherry-pick:

Git cherry-pick is a command that allows you to select specific commits from one branch and apply them to another. This can be useful when you want to selectively apply changes that were made in one branch to another.

To use git cherry-pick, you first create two new branches and make some commits to them. Then you use the git cherry-pick <commit_hash> command to select the specific commits from one branch and apply them to the other.

Resolving Conflicts:

Conflicts can occur when you merge or rebase branches that have diverged, and you need to manually resolve the conflicts before it can proceed with the merge/rebase. git status command shows the files that have conflicts, the git diff command shows the difference between the conflicting versions and the git add command is used to add the resolved files.

Task-01

Create a new branch and make some changes to it.

Use git stash to save the changes without committing them.

Switch to a different branch, make some changes and commit them.

Task-02

In version01.txt of development, the branch adds the below lines after “This is the bug fix in development branch” that you added in Day10 and reverted to this commit.

Line2>> After bug fixing, this is the new feature with minor alterations”

Commit this with the message “ Added feature2.1 in development branch”