## Git & GitHub

_Contents_
* When you should and should not use git ?
* 3 concepts in git: repositories, branches, commits
* Overview of a typical workflow as a contributor: 
  * forking
  * cloning
  * making local changes
  * pushing changes
  * lodging PRs
  * keeping your fork up-to-date

_Case study_
* Working as an in-house contributor (with write rights) vs. working as a guest contributor (w/o write rights) on GitHub

## Credentials

_Contents_
* How to manage git credentials (ssh + gpg) / maybe add “sign-off” too
* Short explanation why “ssh” and “gpg” is important (show security reasons with example shortly
* Explaining how to add “ssh” key into your “X,Y,Z” git provider
* Explaining how to add “gpg” key into your “X,Y,Z” git provider
managing branches and remotes

_Case study_
* How to share credentials with your team?
* What to do when you have erroneously committed contents to a remote repository, e.g. in a commit to a pending Pull Request?

## Managing branches

_Contents_
* cloning, pulling, pushing, fetching, syncing
  * git clone
  * git pull
  * git push remote_name branch_name
  * git fetch

_Case study_
* How do I make sure I am not missing updates from other contributors, across all branches?

## Managing files

_Contents_
* Tracking vs untracking files:
  * gitignore
  * removing
  * adding
  * tips for managing untracked important files
  * `.gitignore`, cleaning local cache

_Case study_
* I have just added/removed a file to/from my `.gitignore`, but git still wants / does not want to commit it

## Managing commits

_Contents_
* Important git commands:
  * “git add .”
  * “git add foo foo2”
  * “git reset foo”
  * “git reset”
  * “git reset --hard”
* forcing commands, what is git force?
* merging vs rebasing
  * reverting
  * resetting (again)
  * rebasing with cherry-picking

_Case study_
* I have just pushed something I should not have, how can I remove it from the remote?
* Last week I pushed something I should not have and there has been several commits since; how can I remove it?
* I have just pulled and now there are conflicts on my branch, what should I do?
