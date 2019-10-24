# Trainer Notes

# Setting up a repository
git init /git clone /git config

## [configure-git](configure-git/README.md)

# Saving changes
git add / git commit / git diff / git stash / .gitignore

## [basic-commits](basic-commits/README.md)
Very basic creation of commits.

## [basic-staging](basic-staging/README.md)
interacting with the stage (index).

## [basic-stashing](basic-stashing/README.md)
The first stride into stashing.

## [ignore](ignore/README.md)
The basics of using the `.gitignore` file.

# Inspecting a repository
git status / git tag / git blame

# Undoing Commits & Changes
git checkout / git clean / git revert / git reset / git rm

## [basic-cleaning](basic-cleaning/README.md)
Cleaning the workspace.

## [basic-branching](basic-branching/README.md)
The first stride into branching.

## [Bad-commit](bad-commit/README.md)
Cleaning up a bit.

## [reset](reset/README.md)
Reset is a powerful and slightly dangerous command if you do not know what you are doing.
Go trough the three modes of resetting here.

# Rewriting history
Git commit --amend and other methods of rewriting history

##[amend](amend/README.md)

## [reorder-the-history](reorder-the-history/README.md)
We might have created our commits in a suboptimal order, practice to fix that scenario here.

## [squashing](squashing/README.md)
A lot of small commits is good when you are working locally, but for sharing your code, it might be more beneficial to deliver your code changes in large sets. Go here to experiment with that.

## [save-my-commit](save-my-commit/README.md)
Should you accidentally or on purpose delete a commit, go here to try and save it.


# Using Branches
git branch / git checkout / git merge

## [basic-branching](basic-branching/README.md)
The first stride into branching.

## [merge-conflict](merge-conflict/README.md)
A basic merge between diverging branches with incompatible changesets.

## [ff-merge](ff-merge/README.md)
A tour around the most trivial of merges.

## [3-way-merge](3-way-merge/README.md)
A basic merge, involving multiple diverged branches.

## [merge-mergesort](merge-mergesort/README.md)
A merge conflict with actual code.

## [reverted-merge](reverted-merge/README.md)
A merge has to be reverted, but this causes problems.

## [commit-on-wrong-branch](commit-on-wrong-branch/README.md)
An administrative exercise, how do we _move_ a commit that we accidentally put on the wrong branch.

## [commit-on-wrong-branch-2](commit-on-wrong-branch-2/README.md)
Another exercise on what to do if you have accidentally committed
on the wrong branch.

## [rebase-branch](rebase-branch/README.md)
Using rebase as an alternative to merging.

## [Advanced interactive rebase](advanced-rebase-interactive/README.md)

# Advanced Git

## [pre-push](pre-push/README.md)
A quick exercise in using Git hooks.

## [submodules](submodules/README.md)
Submodules are loathed by many. Run through this exercise to see what the ruckus is all about.

## [Investigation](investigation/README.md)
Discover what is going on in a Git repo, figure out what it looks like under the hood.

## [Objects](objects/README.md)
A small exercise into Git internals.
