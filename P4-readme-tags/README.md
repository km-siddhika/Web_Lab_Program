# P4 – GitHub README and version tags

**Aim:** Write basic project documentation and mark a version with a Git tag.

A README can describe the project, its purpose, the files included and the steps needed to run it.

```bash
git add README.md
git commit -m "Update project documentation"
git tag -a v1.0 -m "First lab version"
git tag
git push origin main
git push origin v1.0
```

**What this covers:** A tag gives a name to a particular point in the repository history. An annotated tag can also include a message.
