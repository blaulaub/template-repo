# Latex Article Template Repo

This is a meta repository for bootstrapping new Latex articles.
Templates for more specific Latex article types are kept in branches.
To start a new article, just clone the suitable branch and adapt it.

## How to clone

Assuming you want to start a new project with a project folder `$PROJECT`,
clone from the template branch with the following three steps:

```
git clone --single-branch -b Latex-article -o template git@github.com:blaulaub/template-repo.git "$PROJECT"
cd "$PROJECT"
git branch -m Latex-article master
```

The resulting project folder will contain a branch `master` with an upstream
branch `template:Latex-article`.

## Files to Adjust

When starting a new document by cloning from this branch, you should edit the
following files to match your new document:

- `README.md` is this text you are just reading
- `LICENSE` is currently a copy of the MIT License
- `main.tex` is the Latex document

## More Specific Template Branches

- _currently none_
