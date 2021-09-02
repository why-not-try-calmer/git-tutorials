## Introduction
* When you should and should not use git ?
* Working as a foreign contributor, the 10000 feet overwiew: forking, cloning, making local changes, pushing changes, lodging PRs, staying up-to-date, syncing
* Working as an in-house contributor, the 10000 feet overwiew: same except forking

## Credentials
* How to manage git credentials (ssh + gpg) / maybe add “sign-off” too
* Short explanation why “ssh” and “gpg” is important (show security reasons with example shortly
* Explaining how to add “ssh” key into your “X,Y,Z” git provider
* Explaining how to add “gpg” key into your “X,Y,Z” git provider
managing branches and remotes

## Branch management
* Create branch / sync with remote
* Fetch a branch from remote
* Tracking vs untracking files: gitignore, removing, adding, tips for managing untracked important files
* Adding `.gitignore`, cleaning cache
  * “git add .”
  * “git add foo foo2”
  * “git reset foo”
  * “git reset”
  * “git reset --hard”

## Repositoy management
* cloning, pulling, pushing, fetching, syncing
  * git clone
  * git pull
  * git push remote_name branch_name
  * git fetch
  * forcing commands
* what is git force?
* merging, rebasing
* reverting, resetting (again), rebasing with cherry-picking
