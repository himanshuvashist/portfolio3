---
title: "Git for beginners"
date: "2022-01-16"
draft: false
path: "/blog/git-for-beginners"
---

### [Just show me the basic commands](#commands)

### What even is git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Git is a tool if you once start using it you are never going to go back. This tool is not only restricted to coders but everyone who needs to track their digital work such as writers or digital artists can also make use of it.

<h2 id="commands"> Here are few commands to get you started with </h2>

- [git init](#git-init)
- [git clone](#git-clone)
- [git status](#git-status)
- [git diff](#git-diff)
- [git add](#git-add)
- [git commit](#git-commit)
- [git branch](#git-branch)
- [git checkout](#git-checkout)
- [git fetch](#git-fetch)
- [git merge](#git-merge)
- [git pull](#git-pull)
- [git push](#git-push)

<h4 id="git-init">git init</h4>

```sh
git init
```

initialize git in the current repository

```sh
git init [project-name]
```

Creates a new local repository with the specified name

<h4 id="git-clone">git clone</h4>

```sh
git clone [url]
```

Downloads a project and its entire commit hitory

<h4 id="git-status">git status</h4>

```sh
git status
```

Lists new files and modified files to be commited

<h4 id="git-diff">git diff</h4>

```sh
git diff
```

tells what has been changed in files since last commit

```sh
git diff --staged
```

tells what has been changed in staged files since last commit

<h4 id="git-add">git add</h4>

```sh
git add [file]
```

add file to the staging area so it will get added to the next commit

<h4 id="git-commit">git commit</h4>

```sh
git commit -m [message]
```

commit all staged changes

<h4 id="git-commit">git log</h4>

```sh
git log
```

show commit logs for the current branch

<h4 id="git-branch">git branch</h4>

```sh
git branch
```

show all branches

```sh
git branch [new-branch]
```

creates new branch

<h4 id="git-checkout">git checkout</h4>

```sh
git checkout
```

using this we can checkout to any branch/commit

```sh
git checkout -b [new-branch]
```

creates a new branch and checkout to it as the same time

<h4 id="git-fetch">git fetch</h4>

```sh
git fetch
```

download all the branches from remote

<h4 id="git-merge">git merge</h4>

```sh
git merge [branch]
```

merge branch into the current one

<h4 id="git-pull">git pull</h4>

```sh
git pull
```

download the remote branch and merge at the same time

<h4 id="git-push">git push</h4>

```sh
git push
```

push current local branch to remote

# some resources

<a href="https://learngitbranching.js.org" rel="noreferrer noopener" target="_blank">learn git branching</a>
