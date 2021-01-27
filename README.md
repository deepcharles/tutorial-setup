# Setup instructions for tutorials

This repository contains setup instructions for tutorials that I give.
Each folder contains information related to a tutorial.

## Git and GitHub
If you have not set up git and GitHub yet, please follow the following guides:

- [Set up Git](https://docs.github.com/en/github/getting-started-with-github/set-up-git)
- [Authentification with GitHub](https://docs.github.com/en/github/getting-started-with-github/set-up-git#next-steps-authenticating-with-github-from-git)

A small cheatsheet for git: [link](https://github.com/henryiii/compclass/blob/master/classes/week3/HowGitWorks2_0b.pdf).

## Typical workflows
### Fork and create a pull request

([Extensive guide](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo))

A fork is a copy (that you own) of a repository (that you do not own).
To fork a this repostory, click on **Fork** in the top-right corner of the page.

![](https://docs.github.com/assets/images/help/repository/fork_button.jpg)

Create a local clone of your fork on your computer by running the following command in your terminal (replace YOUR-USERNAME with your GitHub login):

```
git clone https://github.com/YOUR-USERNAME/tutorial-setup
```

Create a branch called `mybranch` using `git checkout -b mybranch` (you can obviously change the branch name).

Make any change you want, then commit and push them on your branch.

[To create a pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork), return the original repository page (https://github.com/deepcharles/tutorial-setup) and above the list of files, click on **Pull request**.

![](https://docs.github.com/assets/images/help/pull_requests/pull-request-start-review-button.png)

Any commit you push to your branch will then be added to this pull request.



