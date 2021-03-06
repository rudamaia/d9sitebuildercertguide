[<< Previous](readme.md)
# Git

Git is a version control tool used by Drupal.

It is recommended you learn [git separately](https://docs.github.com/en/get-started/quickstart/git-and-github-learning-resources), but here are some commonly used commands:

### Basic git commands
- `git add` - Adds files to staging area.
- `git commit` - Commits files to repo.
  - `-a`: Adds all unstaged files.
  - `-m`: Sets commit message from command line.
  - `--amend`: Amends the most recent commit message.
- `git push` - Pushes local repo to a remote repo.
- `git pull` - Incorporates changes from a remote repository into the current branch.
- `git clone` - Clones a remote repo to your local system.
- `git checkout` - Switch to another branch
  - `-b`: Create a new branch prior to switching
- `git rebase` - Changes the history of a commit relative to another commit.
- `git merge` - Merges one branch into another.
- `git reset` - Resets HEAD to specified state.
- `git clean` - Removes unstaged files from working tree.
- `git revert` - Reverts changes made in a commit.
- `git log` - Show commit logs.