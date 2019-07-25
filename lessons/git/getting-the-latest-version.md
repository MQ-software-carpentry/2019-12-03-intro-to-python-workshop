# How to get the latest version of code

## Summary (we'll break this down below)
```
git remote add upstream https://github.com/mq-software-carpentry/2019-07-24-intro-to-python-workshop
git fetch --all
git merge upstream/master
```

## `git remote`

`git remote` is how we configure remote repositories: we can add, remove or
rename them.

```
git remote add upstream https://github.com/mq-software-carpentry/2019-07-24-intro-to-python-workshop
```
**adds** a new remote repository `upstream` with the url `https://github.com/mq-software-carpentry/2019-07-24-intro-to-python-workshop`
(we can find the url to add here by clicking the green `clone` button on the
github page)

We can also see what remote repositories we have set up via
```
git remote -v
```
You should see two remote repositories: `origin` and `upstream`; `origin` is the
"default" name for the first remote repository.

## `git fetch`
`git fetch` allows to get the changes on remote repositories.
`git fetch` by default only gets changes from the "default" remote repository;
using `git fetch --all` gets the changes from all of the remote repositories.

## `git merge`
`git merge` adds the changes from a *branch* to the current *branch*:
`upstream/master` contains the latest changes from the `upstream` remote
repository.
