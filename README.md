# Developer Field Notes

## Command Reference

### Git Basics

- `git status` - Show the current state of the working directory.
- `git add <file>` - Stage a file for the next commit.
- `git commit -m "message"` - Create a commit with a message.
- `git log --oneline` - Show a compact version of the commit history.

### Branches

- `git branch` - List local branches.
- `git branch <branch-name>` - Create a new branch.
- `git switch <branch-name>` - Switch to another branch.
- `git switch -c <branch-name>` - Create and switch to a new branch.

### Remote Repository

- `git fetch` - Get the latest information from the remote without merging it.
- `git pull` - Fetch and integrate remote changes into the current branch.
- `git push` - Push local commits to the remote repository.

## Do Not Commit

Never commit sensitive or unnecessary files to a Git repository.

Examples include:

- Passwords or API keys
- `.env` files containing secrets
- Private credentials
- Large generated files
- Operating system files such as `.DS_Store`

Use `.gitignore` to prevent files that should not be tracked from being committed.
