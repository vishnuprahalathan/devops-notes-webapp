# Git Project Documentation

## Branches Created
- main
- dev
- feature/add-notes-ui

## Workflow
- Code changes in `feature/add-notes-ui`
- Merged via Pull Request into `dev`
- Merged `dev` into `main`
- Created tag `v1.0` for first release

## Commands Used

```bash
# Create new branch
git checkout -b feature/add-notes-ui

# Track and commit files
git add index.html
git commit -m "Add basic UI for notes input"
git push origin feature/add-notes-ui

# Merge and tag
git checkout main
git merge dev
git tag -a v1.0 -m "First release"
git push origin v1.0
