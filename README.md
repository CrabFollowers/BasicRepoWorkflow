# Intro
This GitHub org aims to be a place where we can share and collaborate in different proyects.
Repos in this org will only have a "main" branch.
In this article you can find a basic guideline on how to contribute to these repos.

# Basic fork based workflow
1) From the GitHub UI, fork the repo you want to contribute to into your personal account.
2) Clone the repo from your account to your computer:
```
git clone git@github.com:{user}/{repo_name}.git
```
3) Add the original repo as a remote upstream:
```
git remote add upstream git@github.com:CrabFollowers/{repo_name}.git
```
4) Work in a branch in your personal repo.
5) Push your changes and create a PR once it's ready to be merged to "main" in the original repo.
