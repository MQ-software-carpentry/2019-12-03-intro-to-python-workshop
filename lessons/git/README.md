# Git Lession Notes

Feel free to add additional notes to this file: remember to add, commit and push.

## Quick summary (from http://swcarpentry.github.io/git-novice/reference.html)
### What is version control
 * Version control is like an unlimited ‘undo’.
 * Version control also allows many people to work in parallel.
 * The version control system does not allow people to overwrite each other’s changes blindly, but highlights conflicts so that they can be resolved.
 * Conflicts occur when two or more people change the same lines of the same file.

### Git Properties
 * Git stores all of its repository data in the .git directory.
 * The .gitignore file tells Git what files to ignore.
 * Files can be stored in a project’s working directory (which users see), the staging area (where the next commit is being built up) and the local repository (where commits are permanently recorded).
 * A local Git repository can be connected to one or more remote repositories.
 * Write a commit message that accurately describes your changes.

### Quick command reminder
 * Use git config with the --global option to configure a user name, email address, editor, and other preferences once per machine.
 * git init initializes a repository.
 * git clone copies a remote repository to create a local repository with a remote called origin automatically set up.
 * git status shows the status of a repository.
 * git add puts files in the staging area.
 * git commit saves the staged content as a new commit in the local repository.
 * git push copies changes from a local repository to a remote repository.
 * git fetch copies changes from a remote repository to a local repository.
 * git merge gets the changes from a branch and adds them to current branch.
 * git diff displays differences between commits.
 * git checkout recovers old versions of files.


## Useful resources
 * https://www.youtube.com/watch?v=3m7BgIvC-uQ
 * http://justinhileman.info/article/git-pretty/ - read this when you have a problem
 * http://gitready.com/
 * https://blog.plover.com/prog/two-things-about-git.html
