# Version Control
Version control is a system that records changes to a file or a number of them over time so one can go back to them or recall specific versions later. It helps teams collaborate and manage code changes efficiently.

---

## Difference Between Git and GitHub
- **Git**: This a distributed version control system that tracks changes in source code. It is installed locally and works independently of online platforms.
- **GitHub**: GitHub on the other hand, is a cloud-based hosting service for Git repositories. It provides tools for collaborations, version control management, and other features like  pull requests and issue tracking.


---

## GitHub Alternatives
1. **GitLab**
2. **Bitbucket**
3. **SourceForge**


---

## Difference Between `git fetch` and `git pull`
- **`git fetch`**: Downloads changes from the remote repository to a local machine but does not merge them automatically.
- **`git pull`**: Combines `git fetch` and a merge operation. it downloads changes and automatically integrates them into the current branch.


---

## Git Rebase 
Rebase integrates changes from one branch into another by moving the base of the branch. It replays commits from a branch onto another.
**Command:**
```bash
git rebase branch-name

```

---

## Git Cherry-Pick 
Cherry-pick selects commits from one branch and applies them to another branch.
**Command:**
```bash
git cherry-pick commit-hash
```




