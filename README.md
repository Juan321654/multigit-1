# to add a remote repo
`git remote add <assigned name> <github url to repo>`
## example:
`git remote add development https://github.com/Juan321654/multigit-2.git`

`git remote -v` to check current repos
## example:
`
development     https://github.com/Juan321654/multigit-2.git (fetch)
development     https://github.com/Juan321654/multigit-2.git (push)
origin  https://github.com/Juan321654/multigit-1.git (fetch)
origin  https://github.com/Juan321654/multigit-1.git (push)
`

# to pull changes from the other repo 
`git pull <assigned name> <branch> --allow-unrelated-histories`

## example: 
`git pull development master --allow-unrelated-histories`