# Assignment checklist

Use this checklist to verify your work before submitting. Every item should be checked.

---

## Project setup

- [x] `package.json` exists in root folder
- [x] `package-lock.json` exists (auto-generated)
- [x] `node_modules/` folder exists with cowsay installed

## npm scripts

- [x] `package.json` contains a `"cowsay"` script
- [x] `package.json` contains a `"moo"` script
- [x] `package.json` contains a custom `"favorite"` script with your chosen creature/message
- [x] Running `npm run moo` displays a cow saying "Hello from npm scripts!"
- [x] Running `npm run favorite` displays your custom cowsay

## Student-created documentation

- [x] `docs/tutorial-package-json.md` — explains package.json fields

## README

- [x] `README.md` has a level 1 heading with your project title
- [x] `README.md` includes at least one cowsay ASCII art output
- [x] Cowsay output is wrapped in a code fence (triple backticks)
- [x] README displays correctly on GitHub.com

## Reflection

- [x] `ai-collaboration-summary-template.md` is filled out

## Git history

- [x] Multiple commits (not just one giant commit at the end)
- [x] Commit messages describe what changed
- [x] All changes pushed to GitHub

---

## Quick verification commands

Run these in your terminal to verify your setup:

```bash
# Should show cowsay in dependencies
npm list cowsay

# Should display a cow
npm run moo

# Should display your custom creature/message
npm run favorite
```

## Files to submit

Your GitHub repository should contain:

```text
your-repo/
├── docs/
│   ├── tutorial-package-json.md     (you created)
│   └── (pre-made tutorials and reference docs)
├── node_modules/                    (auto-generated)
├── ai-collaboration-summary-template.md (filled out)
├── package.json                     (with your scripts)
├── package-lock.json                (auto-generated)
└── README.md                        (with cowsay output)
```
