Git Commands
============

A list of my commonly used Git commands CASE SENSITIVE)

### STARTING OUT FROM EXISTING GITHUB REPOSITORY
1. Right click folder > "Git Bash Here" OR Git bash > "cd [C:/path] OR [~/project path]"
2. git clone [project URL]
3. Make changes in project
4. Right click project folder > "Git Bash Here" OR Git bash > "cd [C:/project_path] OR [~/project path]"
5. git add -A (or only specific changes)
6. git commit -m "message"
7. git push -u origin [branch_name]


### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone [https://github.com/user/project_name]` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` OR `git add .`| Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes with a message |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin [https://github.com/user/project_name]` | Add a remote repository |
| `git remote set-url origin [https://github.com/user/project_name]` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git diff [source branch] [target branch]` | Preview changes before merging |

### Terminal Commands

| `pwd` | "print working directory" = Displays current path  |
| `ls` | The ls command will show you ('list') the files in your current directory  |
| `cd /` | Navigate into the root directory (ChromeOS downloads = ~/storage/downloads) |
| `cd ~` | Navigate into your home directory |
| `cd ..` | Navigate up one directory level |
| `rm -r [/directory_path]` | Delete a directory and all of its contents recursively |