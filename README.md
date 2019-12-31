# Kotlin Maven Template Repo

This is a meta repository for bootstrapping new Kotlin Maven projects.
Templates for more specific types of software projects are kept in branches.
To start a new project, just clone the suitable branch and adapt it.

## How to clone

Assuming you want to start a new project with a project folder `$PROJECT`,
clone from the template branch with the following three steps:

```
git clone --single-branch -b kotlin-maven -o template git@github.com:blaulaub/template-repo.git "$PROJECT"
cd "$PROJECT"
git branch -m kotlin-maven master
```

The resulting project folder will contain a branch `master` with an upstream
branch `template:kotlin-maven`.

## Files to Adjust

When starting a new project by cloning from a template branch, you should edit the
following files to match your new project:

- `README.md` is this text you are just reading
- `LICENSE` is currently a copy of the MIT License
- `pom.xml` is the Maven project definition
  - adjust at least `groupId` and `artifactId`

## More Specific Template Branches

- _currently none_
