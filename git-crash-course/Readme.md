## Git Hidden Folder

There is a hidden folder called `.git`, which tells you that our project is a git repo.

If we wanted to create a git repo in a new project we' create the folder and then initialize that repo using `git init`

```
mkdir /workspaces/tmp/new-rpoject
cd /workspaces/tmp/new-project
git init
touch Readme.md
code Readme.md
git status
git add .
# makes changes to Readme.md
git commit -m "add readme file"
```

## Cloning

We can clone three ways: HTTPS, SSH, & GitHub CLI

Since we are using GitHub Codespaces we'll a create temporary directory in our workspace

## HTTPS

## Commits

When we want to commit code we can write git commit which will open up the commit edit message in the editor of choice.

```sh
git commit
```

Make a commit message without opening an editor
```
git config --global core.editor emacs
```

## Branches

## Remotes

## Stashing

## Merging

## Add

When we want to stage changes that will be included in the commit
We can use the . to add all possible files.

```
git add Readme.md
git add .
```

## Reset

Reset allows you to move staged changes to be unstaged.
This is useful when you need to revert all files not to be commited.

```

git add .
git reset
```

> git reset will revert a git add.

## Status

Git status shows you what files will or will not be commited.

```
git status
```

## Gitconfig file

The gitconfig file is what stores your global configurations for git such as email, name, editor and more.

Showing the content of our .gitconfig file
```
git config --list --show-origin
```

## Log

git log will show recent git commits to the git tree


## Push

When we want to push a repo to our remote prigin

```
git push
```
