# Basic Ubuntu & GitHub Commands

A quick cheat sheet of common Ubuntu terminal and Git/GitHub commands.

---

## Ubuntu Commands

| Command | Description | Example |
|---|---|---|
| `pwd` | Show current directory. | `pwd` |
| `ls` | List files and folders. | `ls -la` |
| `cd` | Change directory. | `cd projects` |
| `cd ..` | Go to parent directory. | `cd ..` |
| `mkdir` | Create a directory. | `mkdir my-project` |
| `touch` | Create an empty file. | `touch README.md` |
| `cp` | Copy a file or directory. | `cp file.txt backup.txt` |
| `mv` | Move or rename a file. | `mv old.txt new.txt` |
| `rm` | Delete a file. | `rm file.txt` |
| `rm -r` | Delete a directory recursively. | `rm -r old-project` |
| `cat` | Display file contents. | `cat README.md` |
| `nano` | Edit a file in the terminal. | `nano README.md` |
| `clear` | Clear the terminal. | `clear` |
| `history` | Show previous commands. | `history` |
| `sudo` | Run a command as administrator. | `sudo apt update` |
| `apt update` | Refresh package information. | `sudo apt update` |
| `apt upgrade` | Upgrade installed packages. | `sudo apt upgrade` |
| `apt install` | Install a package. | `sudo apt install git` |
| `apt remove` | Remove a package. | `sudo apt remove git` |
| `which` | Show a command's location. | `which git` |
| `whoami` | Show current user. | `whoami` |
| `chmod` | Change file permissions. | `chmod +x script.sh` |
| `chown` | Change file owner. | `sudo chown user:user file.txt` |
| `grep` | Search text for a pattern. | `grep "hello" file.txt` |
| `find` | Find files or directories. | `find . -name "*.php"` |
| `ps` | Show running processes. | `ps aux` |
| `kill` | Stop a process. | `kill 1234` |
| `curl` | Make an HTTP request. | `curl https://example.com` |
| `wget` | Download a file. | `wget https://example.com/file.zip` |

---

## Git / GitHub Commands

> Git manages your local repository. GitHub hosts Git repositories online.

| Command | Description | Example |
|---|---|---|
| `git --version` | Show Git version. | `git --version` |
| `git config` | Configure Git. | `git config --global user.name "Karim"` |
| `git init` | Create a Git repository. | `git init` |
| `git clone` | Download a repository. | `git clone git@github.com:user/app.git` |
| `git status` | Show repository status. | `git status` |
| `git add` | Stage changes. | `git add file.php` |
| `git add .` | Stage all changes. | `git add .` |
| `git commit` | Save staged changes. | `git commit -m "Add login"` |
| `git log` | Show commit history. | `git log --oneline` |
| `git diff` | Show unstaged changes. | `git diff` |
| `git branch` | List branches. | `git branch` |
| `git branch name` | Create a branch. | `git branch feature/login` |
| `git switch` | Switch branches. | `git switch feature/login` |
| `git switch -c` | Create and switch to a branch. | `git switch -c feature/login` |
| `git merge` | Merge a branch. | `git merge feature/login` |
| `git branch -d` | Delete a local branch. | `git branch -d feature/login` |
| `git remote -v` | Show remote repositories. | `git remote -v` |
| `git remote add` | Add a remote repository. | `git remote add origin git@github.com:user/app.git` |
| `git fetch` | Download remote changes. | `git fetch origin` |
| `git pull` | Fetch and merge remote changes. | `git pull origin main` |
| `git push` | Upload commits. | `git push origin main` |
| `git push -u` | Push and set upstream. | `git push -u origin feature/login` |
| `git stash` | Temporarily save changes. | `git stash` |
| `git stash pop` | Restore stashed changes. | `git stash pop` |
| `git reset` | Unstage or move HEAD. | `git reset HEAD file.php` |
| `git revert` | Create a commit undoing another commit. | `git revert abc1234` |
