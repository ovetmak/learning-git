# Hey Yo! I'm here!

- Papa at home!

Hello to everyone who read this.

Here I'd like to write and track my progress of learing Web development. Since I've already tried and failed once, I came back with learnt lessons and new approach which will help me achive my final goal that is to geather necessary skills to find job in web development.

## 1.07.2025

Main goal for today is to develop optimal roadmap and arrange strict boundaries of what I need and will learn before start of applying for dev jobs. Final result for today wil be a draft list of technologies and time expected to learn them. Then I'll make a checklist that will allow me to follow my progress and stay on track

### Reviewed today

Git commands:

- git init - Initialize a Git repository

Initializes a new Git repository in your current directory by creating a hidden .git folder that tracks all version control data.
📁 After this, Git starts tracking changes to files.

- git status - Check the status of your working directory

Shows which files are:
• Untracked (not added yet)
• Modified (changed since last commit)
• Staged (added and ready to commit)
Useful to see what’s going on before committing.

- git add <file name> - Stage a specific file

Adds the specified file to the staging area, preparing it to be included in the next commit.

- git add . - Stage all changes in the current directory

Adds all new, modified, and deleted files in the current folder (and subfolders) to the staging area.
⚠️ Be careful: it stages everything, including files you might not want to commit (like logs or temporary files).

- git commit -m 'message' - Commit staged changes

Saves a snapshot of the staged changes with a descriptive message.

- git log - Show the commit history

Displays a list of past commits, showing:
• Commit hash
• Author
• Date
• Commit message
Use it to find older versions, see history, or grab a commit hash.

- git checkout <hash number> - Go to a specific commit.

Switches your working directory to the state it was in at a specific commit.

- git checkout main - Switch back to the main branch

Takes you out of detached HEAD mode (if you were in it) and puts you back on the main branch, where active development usually happens.

- git checkout -f main - Force switch to main branch

The -f (force) option discards any uncommitted changes in your working directory, then switches to main.
⚠️ This will delete local changes — use only if you’re sure you don’t need them.

## 2.07.2025

Since yesterday I've stuck on reviewing git, I expect today I'm going to follow up with git and before midday I will compleate my review process, which will allow me to feel free and confident with git.

### Reviewed today

Git commands:

- git branch -M main - Renames the current branch to main. Useful if you want to standardize the default branch name.

- git remote add origin <url> - Adds a remote repository named origin with the given URL. Typically used to connect your local repo to a GitHub repo.

- git remote add <repo-name> <url> - Adds a remote with a custom name other than origin. This is useful if you're working with multiple remotes.

- git push -u origin main - Pushes your local main branch to the remote origin, and links it so future git push or git pull commands work automatically.

- git branch <branch-name> - Creates a new branch pointing to the current commit.

- git checkout <branch-name> - Switches your working directory to another branch.

- git checkout -b <branch-name> - Creates a new branch and immediately switches to it.

- git branch <new-branch-name> <source-branch> - Creates a new branch starting from the commit where source-branch currently points.

- git push --set-upstream origin <branch-name> || - git push -u origin <branch-name> - Pushes the branch to the remote and sets it as the default upstream. After this, you can use just git push.

- git push - Sends your committed changes to the corresponding remote branch.

- git pull - Downloads the latest changes from the remote branch and automatically merges them into your current branch.

- git merge - Merges the changes from a specified branch into your current branch.
  <!-- git checkout main -->
  <!-- git merge feature/login -->
  <!-- This will integrate the changes from feature/login into main. -->

#### Typical workflow

    1. Clone the repo
    2. Create a new branch from the main or another branch
    3. Make changes
    4. Push the branch to the remote repo
    5. Open a Pull Request
    6. Merge the changes
    7. Pull the merged changes into your local main branch
    8. Repeat from step 2
