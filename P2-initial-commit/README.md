# P2 – Portfolio repo with an initial commit

**Aim:** Create a Git repository and save the first version of a portfolio project.

```bash
mkdir portfolio
cd portfolio
git init
echo "# My Portfolio" > README.md
git add README.md
git commit -m "Add initial portfolio README"
git status
```

To connect a GitHub repository, replace the URL with your repository URL:

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git branch -M main
git push -u origin main
```

**What this covers:** `git init` starts version control, `git add` stages a file, and `git commit` records the staged change.
