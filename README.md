# Github-Shortcuts-and-commands
# Github Shortcut Commands


🚀 Git & GitHub Quick Commands Cheat Sheet  

🔹 Setup
git init                        # Initialize a new Git repository
git clone <repo-url>            # Clone a repo from GitHub
git remote -v                   # List remotes
git remote add origin <url>     # Add GitHub repo as remote
git remote set-url origin <url> # Change remote URL

🔹 Branching
git branch                      # List branches
git branch -m master main       # Rename branch
git checkout -b <branch>        # Create and switch to new branch
git switch <branch>             # Switch to an existing branch

🔹 Staging & Committing
git status                      # Check changes
git add .                       # Stage all changes
git add <file>                  # Stage a single file
git commit -m "message"         # Commit changes

🔹 Pushing & Pulling
git push -u origin main         # Push first time (sets upstream)
git push                        # Push changes
git pull origin main            # Pull latest from GitHub

🔹 Undo / Fix
git reset --hard HEAD           # Reset working dir to last commit
git checkout -- <file>          # Discard local changes to file
git restore <file>              # Restore file (newer syntax)

🔹 Logs & History
git log --oneline --graph       # View commits in short graph form
git diff                        # Show unstaged changes
git diff --staged               # Show staged changes

🔹 Removing & Ignoring
git rm <file>                   # Remove file from repo + disk
git rm --cached <file>          # Remove file only from repo
echo "file_or_folder/" >> .gitignore  # Ignore files/folders

⚡ Pro Tip: After creating a repo, the usual first-time sequence is:
git init
git branch -M main
git add .
git commit -m "Initial commit"
git remote add origin <repo-url>
git push -u origin main
