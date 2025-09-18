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

The content is a guide to help users recover from common Git mistakes. It provides plain English solutions to various "Oh shit" scenarios, such as:

1. **Time Machine**: Use `git reflog` to view history and `git reset HEAD@{index}` to revert to a previous state.
2. **Amend Last Commit**: Use `git commit --amend --no-edit` to add changes to the last commit.
3. **Change Commit Message**: Use `git commit --amend` to edit the last commit message.
4. **Accidental Commit to Master**: Create a new branch and reset master using `git branch`, `git reset HEAD~ --hard`, and `git checkout`.
5. **Committed to Wrong Branch**: Use `git reset HEAD~ --soft`, `git stash`, and `git stash pop` to move changes to the correct branch.
6. **Empty Diff**: Use `git diff --staged` to view staged changes.
7. **Undo Old Commit**: Use `git log` to find the commit and `git revert [hash]` to undo it.
8. **Undo File Changes**: Use `git log` to find a previous commit and `git checkout [hash] -- path/to/file` to revert the file.
9. **Reset Repository**: Use `git fetch origin`, `git reset --hard origin/master`, and `git clean -d --force` to reset the repository state.

The guide emphasizes that these solutions are based on practical experience and may not cover all theoretical scenarios. It also includes translations and credits to contributors.
## Links

- [Oh Shit, Git! Repository](https://github.com/ksylor/ohshitgit) : The GitHub repository for the Oh Shit, Git! website, providing practical solutions to common Git problems.
- [Dangitgit](https://dangitgit.com/en) : The same content as Oh Shit, Git! but without swears, providing a more professional tone for the same Git solutions.

## Topics

![[topics/Tool/Git)]]