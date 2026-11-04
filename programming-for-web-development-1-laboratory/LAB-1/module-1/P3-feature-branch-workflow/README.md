# Problem 3: Feature-branch Git workflow

## Aim
To learn the feature-branch Git workflow by creating a branch, adding features, and merging it back into main.

## Commands Used
- `git branch` - list branches
- `git checkout -b` - create and switch to a new branch
- `git status` - check modified files
- `git add` - stage changes
- `git commit` - save changes to branch
- `git checkout` - switch back to main
- `git merge` - merge branch into main
- `git branch -d` - delete merged branch

## Steps
1. Created and switched to feature branch:
```bash
git checkout -b feature-navbar-projects
```

2. Added the navigation bar and project cards in `index.html` and styled them in `styles.css`.

3. Staged and committed the changes:
```bash
git add .
git commit -m "feat: added problem 3 styles"
```

4. Switched back to main and merged:
```bash
git checkout main
git merge feature-navbar-projects
```

5. Removed the feature branch:
```bash
git branch -d feature-navbar-projects
```
