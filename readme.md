# Git Commands
## Clone a repository  

  ```bash
git clone <repo-url>   
``` 
  

## Initialize a new Git repository  
  

  ```bash
git init   
```

## Set global username and email 
  ```bash
 git config --global user.name "MjTamizh"  
git config --global user.email "your.email@example.com"    
``` 


## Add unstaged changes to the staging area  

  ```bash
   
git add .  
```

## Commit staged changes with a message (following Conventional Commits)  
  ```bash
   
git commit -m "message"  
```

## Push changes to the remote repository (main branch or specific branch)  
  ```bash
   
git push origin main  
git push origin <branch> 
``` 

## Pull the latest changes from the remote repository  
  ```bash
   
git pull origin main  
```

## List all branches  
  ```bash
   
git branch  
```

## Create and switch to a new branch  
```bash
   
git checkout -b "ui"  
```

## Switch back to the main branch  
  ```bash
git checkout main  
   
```

## Push a new branch and set upstream tracking  
  ```bash
git push --set-upstream origin ui  
   
```

## Fetch and merge changes from the main branch  
  ```bash
   
git pull origin main  

```
## Merge branches on GitHub (via UI)  

## View commit history with unique hash IDs  
  ```bash
   
git log  
```

## Check the current status of a working directory  
  ```bash
git status   
```
  

## Show differences between files 
  ```bash
   
git diff  
``` 

## Save changes temporarily (like a recycle bin)  
  ```bash
   
git stash  
```

## Restore the most recent stashed changes  
  ```bash
   
git stash pop  
```

## Rename the current branch  
  ```bash
git branch -M "UI"   
```
  

## Show all local and remote branches  
  ```bash
git branch -a     
```


## Reset to a previous commit  
  ```bash
git reset --hard <commit-hash>   
```
  
