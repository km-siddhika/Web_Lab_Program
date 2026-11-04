# P3 – Feature-branch Git workflow

**Aim:** Make a change on a separate branch and merge it into the main branch.

```bash
git switch -c feature/about-section
# Make a change to your project and save it
git status
git add .
git commit -m "Add about section"
git switch main
git merge feature/about-section
git branch
```

To publish the feature branch:

```bash
git push -u origin feature/about-section
```

**What this covers:** A feature branch keeps a change separate while it is being developed. The merge brings the finished work into `main`.
