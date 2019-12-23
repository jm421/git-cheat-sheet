# git-cheat-sheet :man_technologist:


## Commands:

**`git clone <repo link>`**                       = Clones remote repo to current directory

**`git init`**                                    = Creates git repository in the curent directory (creates hidden .git directory)

**`git remote (-v for verbose)`**                 = Show remote repos

**`git branch -a`**                               = Show all branches (local and remote)

**`git add (-a for all or <file_name>)`**         = Add files to 'staging area', i.e. choose specific files to commit

**`git reset (no args for all or <file_name>)`**  = Remove file from 'staging area'

**`git commit -m <commit message>`**              = Commit files in staging area to local repo

**`git push <remote repo> <branch>`**             = Push whatever is committed in the local repo to the remote repp (i.e. github)

**`git pull <remote repo> <branch>`**             = Pull changes from remote repo (e.g. git pull origin master)

**`git status`**                                  = Show which files got modified (differences between local files and local repo)

**`git diff`**                                   = Show changes to files line by line

**`git --version`**                               = Check git version

**`git config --global user.name = <username>`**  = Setting user name for commits
**`git config --global user.email= <email>`**     = Setting email for commits (must match github email!)
**`git config --list`**                           = Show all config values

**`git help <verb> or git <verb> --help`**        = Man page for git verbs



## Steps to update changes (from local to remote):
1) `git add <file>` - Adds file to staging area
1) `git commit -m <message>` - Commits staged files ready for pushing
1) `git pull <remote> <branch>` - Pulls any changes made in the remote repo
1) `git push <remote> <branch>` - Pushes committed files to remote repo



## Other:
**`.gitignore` file**                               = Can be used to tell git to ignore certain files when doing 'add -all' or 'commit -all'
**`.git` directory**                                = Created in current directory after a 'git init'. Contains all necessary version control information.
