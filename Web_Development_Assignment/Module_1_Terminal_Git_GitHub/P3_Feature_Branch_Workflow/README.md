# P3: Feature-branch Git workflow

## Aim
Create a feature branch, make a change and merge it into the main branch.

## Commands
```bash
git branch
git switch -c feature/about-section
```

Make a small change to a project file, then run:

```bash
git status
git add .
git commit -m "Add about section"
git switch main
git merge feature/about-section
git branch
```

## Meaning
- `git switch -c` creates and opens a new branch.
- `git add .` stages changed files.
- `git commit` saves a snapshot.
- `git switch main` returns to the main branch.
- `git merge` combines the feature branch with main.
