# Clone a repository  
git clone <repo-url>  

# Initialize a new Git repository  
git init  

# Set global username and email  
git config --global user.name "MjTamizh"  
git config --global user.email "your.email@example.com"  

# Add unstaged changes to the staging area  
git add .  

# Commit staged changes with a message (following Conventional Commits)  
git commit -m "message"  

# Push changes to the remote repository (main branch or specific branch)  
git push origin main  
git push origin <branch>  

# Pull the latest changes from the remote repository  
git pull origin main  

# List all branches  
git branch  

# Create and switch to a new branch  
git checkout -b "ui"  

# Switch back to the main branch  
git checkout main  

# Push a new branch and set upstream tracking  
git push --set-upstream origin ui  

# Fetch and merge changes from the main branch  
git pull origin main  

# Merge branches on GitHub (via UI)  

# View commit history with unique hash IDs  
git log  

# Check current status of working directory  
git status  

# Show differences between files  
git diff  

# Save changes temporarily (like a recycle bin)  
git stash  

# Restore the most recent stashed changes  
git stash pop  

# Rename the current branch  
git branch -M "UI"  

# Show all local and remote branches  
git branch -a  

# Reset to a previous commit  
git reset --hard <commit-hash>  
