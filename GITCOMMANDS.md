## Development Procedure: 
To ensure master branch is stable
1. Make changes on a new branch (not master)
2. Test changes on the new branch 
3. Commit and push changes on the new branch
4. Merge master into the new branch (to resolve any merging conflicts and keep master clean)
5. Merge new branch back into master
(Note: members should not be working on the same branch to avoid conflict issues)

## Quick Git commands:
Branching
1. Check what branch you are on: `git status`
2. Create a branch: `git branch 'branchname'`
3. Move to a branch: `git checkout 'nameofbranch'`
4. Create a branch and move to it (command 2 and 3 combined):  `git checkout -b 'nameofbranch'`

## Fetching/Pulling/Merging
1. Get files from branch (does not overwrite existing changes in local repo): `git fetch 'branch'`
2. Get files from branch and merge with the branch you are on: `git pull 'branch'`
3. Merge files to what branch you are on: `git merge 'sourcebranch'`

## Remove changes
1. Remove uncommitted changes: `git checkout .`
2. Remove unpushed commits: `git reset`
