<h2> Cheat Sheet</h2>

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - View file differences not yet staged

#### Repo History
`$ git log` - Lists version history for current branch

`$ git log --oneline --decorate --color --graph --all` - makes log more easily legible, all parameters customizable and affect different aspects of log  

`$ git log -p [filename]` Shows history of commits associated with file and what was changed/made within them

#### Stage files to commit
`$ git add <filename>` - add file contents to index

`$ git add -A` - adds everything in current path

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__