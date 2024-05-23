# US-letter-marp

[Marp](https://marp.app/) CSS theme to do US-letter documents with markdown. Dark Mode, using Uncover Theme from Marp, and Atom One Dark Theme for code highlighting. Forked from stanfrbd [A4-marp](https://github.com/stanfrbd/A4-marp)

The folder `.vscode` and the Marp plugin are mandaory to make it work.

Assuming VS Code and [Marp for VS Code](https://github.com/marp-team/marp-vscode) are already installed:

- Clone this project
- Open this entire folder in VS Code
- Start writing your `.md` file using

You need to have the folder `.vscode` + `settings.json`

## Dark theme

Put

```markdown
---
marp: true
theme: us-letter-dark
paginate: true
---
```

at the beginning of the `.md` file.


## Light theme

Put

```markdown
---
marp: true
theme: us-letter-light
paginate: true
---
```

at the beginning of the `.md` file.