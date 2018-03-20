## Here are some useful git commands


# configure git
	`git config --global user.name username`
	`git config --global user.email user@name.com`

# configuring defualt text editor
   `git config --global core.editor emacs`

# make directory ready to use as a git repository
	`git init`

# tell git where the repository is on github.com (for a remote repository)
# note use lancsDSRG in place of username
	`git remote add origin https://github.com/username/repository`

# add file "README" to the list (one file called README)
	`git add README`

# add all files in the directory
- `git add .`
- or just the files we have told git to track: `git add --update`

# commit
	`git commit -m `first commit`

# push to repository on github
	`git push origin master`

# list the tracked files on the master branch
   	`git ls-tree -r master --name-only`

# for setting path to use ssh 
`git remote set-url origin git@github.com:username/repo.git`

# Check status of repository
`git status`

# view differences
   `git diff`	


# Logs of commits:
- `git log`
- short logs: `git log --oneline`

# Reverting to previous commits:
- `git revert HEAD^`, this reverts to the version before the current commit
- `git revert HEAD^^`, to the two previous and generally `git revert HEAD~n`, for n before the current version

# cloning a repository into a local one with name "test_repo"
- `git clone https://github.com/username/repository test_repo`


## More advanced topics, Branching:
# Add new branch: `git brach branch_name`

# View all branches `git branch`

# switch to new branch `git checkout branch_name`

# Merging a branch, be on the branch that we will merge into.

 
