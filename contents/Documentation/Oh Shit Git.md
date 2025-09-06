---
already_read: true
link: https://ohshitgit.com/
read_priority: 0
relevance: 4
source: null
tags:
- Development_tool
type: Content
upload_date: '2025-04-27'
---

https://ohshitgit.com/
## Summary

This content is a guide to help users recover from common Git mistakes. It provides practical solutions to typical Git problems in plain English. Here are the key takeaways:

1. **Time Machine with `git reflog`**: Use `git reflog` to view a list of all actions performed in Git, then use `git reset HEAD@{index}` to revert to a previous state.

2. **Amending the Last Commit**: To make a small change to the last commit, use `git commit --amend --no-edit`. For changing the commit message, use `git commit --amend`.

3. **Moving Commits to a New Branch**: If you committed to the wrong branch, create a new branch with `git branch some-new-branch-name`, remove the commit from the master branch with `git reset HEAD~ --hard`, and then switch to the new branch.

4. **Undoing a Commit from the Wrong Branch**: Use `git reset HEAD~ --soft` to undo the commit but keep the changes, then `git stash` to save them. Move to the correct branch, `git stash pop` to apply the changes, and commit them.

5. **Viewing Staged Changes**: If `git diff` shows nothing, use `git diff --staged` to view staged changes.

6. **Reverting a Specific Commit**: Use `git log` to find the commit hash, then `git revert [saved hash]` to create a new commit that undoes the changes.

7. **Undoing Changes to a File**: Use `git log` to find a commit hash before the file was changed, then `git checkout [saved hash] -- path/to/file` to restore the old version of the file.

8. **Resetting a Borked Repository**: If the repository is severely damaged, fetch the latest state of the origin, reset the branch to match the origin, and clean untracked files with `git clean -d --force`.

The guide emphasizes practical solutions and includes warnings about the consequences of certain actions, such as amending public commits. It also acknowledges that there are other ways to achieve the same results but focuses on methods that the author has found effective through trial and error.
## Links

- [Oh Shit, Git!?! GitHub Repository](https://github.com/ksylor/ohshitgit) : The GitHub repository for the Oh Shit, Git!?! website, containing the source code and translations.
- [Dangitgit](https://dangitgit.com/en) : The same content as Oh Shit, Git!?! but without swears.

## Topics

![](topics/Tool/Git)