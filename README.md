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

## Git Practice Evidence

aadityakoirala@MacBookPro developer-field-notes % git log --oneline
git log --oneline --graph --all
git branch --all
bede3e0 (HEAD -> main, origin/main, origin/HEAD) Merge pull request #6 from aadikoi92/feature/responsive
47023ba (origin/feature/responsive, feature/responsive) Improve responsive styling
2fbf2fb Merge pull request #5 from aadikoi92/feature/safety
221c87e (origin/feature/safety, feature/safety) Add do not commit safety section
6d4baf7 Merge pull request #4 from aadikoi92/feature/command
04ecea1 (origin/feature/command, feature/command) Add Git command reference
30b40cc third: initial css added
096efa2 second: initial HTML and README added
fb92920 first: .gitignore committed

- bede3e0 (HEAD -> main, origin/main, origin/HEAD) Merge pull request #6 from aadikoi92/feature/responsive
  |\  
  | \* 47023ba (origin/feature/responsive, feature/responsive) Improve responsive styling
  |/
- 2fbf2fb Merge pull request #5 from aadikoi92/feature/safety
  |\  
  | \* 221c87e (origin/feature/safety, feature/safety) Add do not commit safety section
  |/
- 6d4baf7 Merge pull request #4 from aadikoi92/feature/command
  |\  
  | \* 04ecea1 (origin/feature/command, feature/command) Add Git command reference
  |/
- 30b40cc third: initial css added
- 096efa2 second: initial HTML and README added
  :
