# Portfolio Git Demo

A two-page HTML and CSS portfolio for practicing Git. Open index.html in a browser to read the introduction and browse the sample projects.

## Branches

- main holds the stable version.
- develop starts from main and integrates feature changes.
- feature/portfolio starts from develop and holds portfolio improvements.

## Workflow

Commit changes on the feature branch. Switch to develop and merge feature/portfolio. If Git reports a conflict, review both versions, edit the file, remove the conflict markers, stage the resolved file, and commit the merge. Review the integrated site, then switch to main and merge develop.
