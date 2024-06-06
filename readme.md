First Project
Author- Aharan SE
Ontash Tech India
git reset: Move the HEAD and current branch to a specified commit, optionally resetting the staging area and/or the working directory to match.

git rebase: Reapply commits from one branch onto another. It's commonly used to maintain a linear commit history and integrate changes from one branch into another.

git cherry-pick: Apply specific commits from one branch to another. This is useful when you want to pick only certain commits from one branch and apply them to another.

git reflog: View the reference log, which records updates to the HEAD reference over time. It's helpful for recovering lost commits or branches.

git bisect: Use binary search to find the commit that introduced a bug. It's useful for identifying which commit caused a regression in your codebase.

git submodule: Manage submodules within your Git repository. Submodules allow you to include other Git repositories as subdirectories in your project.

git stash: Temporarily store changes in the working directory that are not ready to be committed. Stashed changes can later be applied or dropped.

git filter-branch: Rewrite branches by applying custom filters to commit history. It's useful for removing sensitive data or large files from the repository history.

git remote prune: Remove remote branches that no longer exist on the remote repository.

git log --graph: Visualize the commit history as a graph, showing branching and merging.

git worktree: Manage multiple working trees attached to the same repository. It allows you to work on different branches simultaneously without switching back and forth.

git revert: Create a new commit that undoes the changes introduced by a previous commit. Unlike git reset, git revert doesn't alter the existing commit history.