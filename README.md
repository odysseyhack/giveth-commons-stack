# Giveth Commons Stack
Redefining Donation Driven Organizations  

## The "Augmented Bonding Curve" Stack
[Web App](./giveth-commons-abc-app)  
[JS Library](./giveth-commons-abc-lib)  
[EVM Contracts](./giveth-commons-abc-contracts)  

## Development Setup
1. Clone this repo.  
2. Run the `./setup.sh` script (`.cmd` on Windows).  

## Pushing Your Code (Twice)
This repo is a "Mono Repo" that makes use of "Git Submodules", which are equivalent to "Nested Repos".  

This means that when you make changes to your project, and push new commits to its master branch, there is an extra step needed to update this root repository (the monorepo).

Simply `cd` into this directory, `git status` should show changes in your repo's folder. Just `git add *` and `git commit ...` and the new commit hash of your repo will be pushed to this repo.

## Adding Your Repo
`git submodule add https://....`  
`git add *`  
`git commit ...`  
`git push`  
