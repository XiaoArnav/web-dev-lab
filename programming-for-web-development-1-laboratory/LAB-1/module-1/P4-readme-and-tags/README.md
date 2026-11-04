# Problem 4: GitHub README and Version Tags

## Aim
To document the web development developer portfolio project using a comprehensive Markdown README, implement semantic release notes, and establish milestone release version tags (`v1.0.0`) using Git and GitHub.

---

## Objectives
1. Author an informative, structured `README.md` covering project background, technology stack, directory layout, and execution steps.
2. Build an accessible, semantic HTML5 release overview page (`index.html`) styled with clean responsive CSS (`styles.css`).
3. Apply Semantic Versioning (`MAJOR.MINOR.PATCH`) to track milestone releases.
4. Create an annotated Git tag (`v1.0.0`) with release message and author metadata.
5. Push the branch and annotated tags to GitHub (`origin/main`).
6. Verify release tags and repository status via the Git CLI and GitHub web interface.

---

## Commands Used

| Command | Description |
| :--- | :--- |
| `git status` | Verify working tree status and check for unstaged changes |
| `git add <files>` | Stage release documentation, HTML, and CSS assets |
| `git commit -m "<msg>"` | Record milestone snapshot with conventional commit format |
| `git tag -a <tagname> -m "<msg>"` | Create an annotated Git tag with descriptive message and metadata |
| `git tag` / `git tag -l` | List all existing release tags in the local repository |
| `git show <tagname>` | Display detailed tag metadata, author, date, and commit diff |
| `git push origin <branch>` | Synchronize committed code to remote GitHub branch |
| `git push origin <tagname>` | Push a specific annotated tag to GitHub remote |
| `git push origin --tags` | Push all local tags to GitHub remote simultaneously |
| `git checkout <tagname>` | Inspect working tree state at a specific tagged release |

---

## Step-by-Step Implementation

### Step 1: Navigating to the Problem Directory
```bash
cd programming-for-web-development-1-laboratory/LAB-1/module-1/P4-readme-and-tags
```

### Step 2: Creating Semantic Release HTML & Stylesheet
Created `index.html` featuring semantic landmarks:
- `<nav>` with sticky anchor links
- `<header>` highlighting developer identity and `<span class="badge">v1.0.0</span>`
- `<section>` blocks for About This Release, Tech Stack, Module 1 Deliverables, Release Notes, and Repository Details
- `styles.css` providing responsive styling, card layouts, and typography tokens.

### Step 3: Staging and Committing Problem 4 Deliverables
```bash
git add index.html styles.css README.md
git commit -m "feat: complete problem 4 github readme and version tags" \
  --author="XiaoArnav <322868724+XiaoArnav@users.noreply.github.com>"
```

### Step 4: Creating the Annotated Release Tag (v1.0.0)
Semantic Versioning follows `vMAJOR.MINOR.PATCH`:
- `v1.0.0` denotes the first stable production release completing Module 1.

```bash
git tag -a v1.0.0 -m "Release v1.0.0: Module 1 Terminal, Git and GitHub completed"
```

### Step 5: Inspecting Tag Metadata
```bash
git show v1.0.0
```

### Step 6: Synchronizing with GitHub Remote
```bash
git push origin main
git push origin v1.0.0
```

---

## Module 1 Milestone Summary

| Problem | Focus Area | Deliverable | Status |
| :--- | :--- | :--- | :---: |
| **P1** | Terminal Navigation | Directory tree scaffolding via CLI | Completed |
| **P2** | Initial Git Repository | `git init`, user config, initial commit | Completed |
| **P3** | Feature Branch Workflow | Isolated feature branch, development & merge | Completed |
| **P4** | Documentation & Tags | Project README & annotated tag `v1.0.0` | **Completed** |

---

## Verification & Output

### 1. Tag Listing Verification
```bash
$ git tag -l -n
v1.0.0          Release v1.0.0: Module 1 Terminal, Git and GitHub completed
```

### 2. Git Log Graph
```bash
$ git log --oneline --graph -n 4
* 40bee50 (HEAD -> main, tag: v1.0.0, origin/main) feat: complete problem 4 github readme and version tags
* 195c8dd feat: added problem 4 styles
* 5478f2f feat: added problem 4 html
* 5d1c10f feat: added problem 3 styles
```

---

## Learning Outcomes
1. Mastered project documentation standards using GitHub Flavored Markdown.
2. Understood the difference between lightweight tags (`git tag v1.0.0`) and annotated tags (`git tag -a v1.0.0 -m "..."`).
3. Learned how annotated tags preserve author cryptographic timestamps and release notes in Git history.
4. Successfully concluded Module 1 (Terminal, Git & GitHub) with a tagged milestone release.
