# P3: Feature-branch Git workflow

Practise making a change on a separate Git branch and sending it to GitHub.

## Steps
1. Open the project folder.
2. Create and switch to a new branch.
3. Make a small change to a file.
4. Commit the change.
5. Push the branch to GitHub.

## Commands
```bash
git switch -c feature/about-section
git status
git add .
git commit -m "Add about section"
git push -u origin feature/about-section
```

## Merge the change
On GitHub, open a pull request from `feature/about-section` into `main`. Review it and merge it when ready.

## What I learned
A branch lets me work on a change separately without directly changing the main branch.

---

[Back to the repository homepage](../index.html)
