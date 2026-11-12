# P3: Feature-branch Git workflow

## Objective
Create a feature branch, commit a change, and merge it back.

## Files
- README.md — objective and implementation notes.

## Commands
```bash
git switch -c feature/about-section
# edit files
git add .
git commit -m "Add about section"
git switch main
git merge feature/about-section
```
