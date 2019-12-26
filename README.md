# Latex Template Repo

This is a meta repository for bootstrapping new Latex documents.
Templates for more specific Latex document types are kept in branches.
To start a new document, just clone the suitable branch and adapt it.

## How to clone

Assuming you want to start a new project with a project folder `$PROJECT`,
clone from the template branch with the following three steps:

```
git clone --single-branch -b Latex -o template git@github.com:blaulaub/template-repo.git "$PROJECT"
cd "$PROJECT"
git branch -m Latex master
```

The resulting project folder will contain a branch `master` with an upstream
branch `template:Latex`.

## Files to Adjust

When starting a new document by cloning from this branch, you should edit the
following files to match your new document:

- `README.md` is this text you are just reading
- `LICENSE` is currently a copy of the MIT License
- `main.tex` is the Latex document

## More Specific Template Branches

- [Latex-article](https://github.com/blaulaub/template-repo/tree/Latex-article)
