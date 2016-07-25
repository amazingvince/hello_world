# Learing Git

## What is Git

Git is a distributed version control system.  You can read all the details on line at

https://git-scm.com/book/en/v2

An interesting talk Linus gave about the motivations behind Git is here

https://www.youtube.com/watch?v=4XpnKHJAok8

Warning: Linus is kind of a git himself!

## The least you need to know

These are the commands you are going to use all the time:

| Command | What it does? |
|---------|---------------|
| `git clone` | Copy repository (usually from GitHub) to your local machine |
| `git merge` | Merge from one branch into another branch |
| `git fetch` | Pull data from a remote repository to your local remote reference |
| `git pull`  | Do both a `fetch` and a `merge` from a remote repo into your tracking branch |
| `git checkout` | Change your current branch |
| `git checkout -b 'new branch name'` | Create a new branch named `new branch name` based off of the current branch |
| `git add` | Add files to the index |
| `git commit` | Commit files from the index to the repo |
| `git commit -am 'commit message here'` | Commit files with the message 'commit message here', automatically adding new files (skipping `git add`) |
| `git push` | Push your local data to a remote (usually, GitHub) |
| `git status` | Show information about your current branch, working directory, and index |
| `git diff` | Show differences that you haven't committed yet |

There are a zillion more.

## Some GitHub specific stuff

GitHub has some helpful things:

1. [GitHub Flavored Markdown](https://help.github.com/categories/writing-on-github/)
1. [SSH Support](https://help.github.com/categories/ssh/)
1. [Pull Requests](https://help.github.com/articles/using-pull-requests/)

## Beyond the Basics

Eventually, you'll want to avoid checking directly into `master`.  And you'll want to use a mess of branches.  Choosing a good branching model will be helpful.  This is a common one:

http://nvie.com/posts/a-successful-git-branching-model/

You'll definitely want to set up SSH access.  If you go into the technical part of tech, SSH will be a ubiquitous phenomenon.  May as well get used to setting it up now!
