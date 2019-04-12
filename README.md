# Giveth Commons Stack

## Development Setup
1. Clone this repo.  
2. Run the `./setup.sh` script (`.cmd` on Windows).  

## Pushing Your Code (Twice)
This repo is a "Mono Repo" that makes use of "Git Submodules", which are equivalent to "Nested Repos".  

This means that when you make changes to your project, and push new commits to its master branch, there is an extra step needed to update this root repository (the monorepo).

Simply `cd` into this directory, `git status` should show changes in your repo's folder. Just `git add *` and `git commit ...` and the new commit hash of your repo will be pushed to this repo.

# TODO
- Instructions for creating a new dApp with the commons-stack
