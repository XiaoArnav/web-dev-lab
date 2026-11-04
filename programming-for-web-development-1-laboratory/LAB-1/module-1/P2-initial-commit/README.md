# Problem 2: Portfolio repo with an initial commit

## Aim
To initialize a git repository for a developer portfolio and create the starter files.

## Commands Used
- `git init` - initialize a new git repository
- `git config` - set user name and email
- `git status` - check working tree status
- `git add` - stage files for commit
- `git commit` - save snapshot to repository
- `git log` - view commit history

## Steps
1. Initialized git repository:
```bash
git init
```

2. Configured user details:
```bash
git config user.name "XiaoArnav"
git config user.email "322868724+XiaoArnav@users.noreply.github.com"
```

3. Created portfolio starter files (`index.html`, `styles.css`):
```bash
touch index.html styles.css
```

4. Staged and committed the files:
```bash
git add .
git commit -m "feat: added problem 2 styles"
```

5. Checked git history:
```bash
git log --oneline
```
