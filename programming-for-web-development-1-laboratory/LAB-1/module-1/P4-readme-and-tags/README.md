# Problem 4: GitHub README and version tags

## Aim
To learn how to write a project README and create a release version tag in Git.

## Commands Used
- `git tag` - list existing tags
- `git tag -a -m` - create an annotated tag with a message
- `git show` - display tag details
- `git push origin <tag>` - push the tag to GitHub

## Steps
1. Created the release page `index.html` and styled it in `styles.css`.

2. Created an annotated version tag for the completed module:
```bash
git tag -a v1.0.0 -m "Module 1 completed"
```

3. Verified the tag:
```bash
git tag
git show v1.0.0
```

4. Pushed the tag to GitHub:
```bash
git push origin v1.0.0
```
