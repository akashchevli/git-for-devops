# Git Basic Commands

## 1. Initialize a Repository
git init

## 2. Clone a Repository
git clone <repository-url>

## 3. Check Status
git status

## 4. Add Changes to Staging
git add <file-name>  
or to add all changes:  
git add .

## 5. Commit Changes
git commit -m "Your commit message"

## 6. View Commit History
git log

## 7. Branching
### Create a New Branch
git branch <branch-name>

### Switch to a Branch
git checkout <branch-name>

### Create and Switch to a New Branch
git checkout -b <branch-name>

## 8. Merging Branches
git merge <branch-name>

## 9. Push Changes to Remote
git push origin <branch-name>

## 10. Pull Changes from Remote
git pull origin <branch-name>

## 11. Delete a Branch
### Locally
git branch -d <branch-name>  

### Remotely
git push origin --delete <branch-name>

## 12. Stashing Changes
### Stash Changes
git stash  

### Apply Stashed Changes
git stash apply

## 13. Viewing Remote Repositories
git remote -v

## 14. Adding a Remote Repository
git remote add origin <repository-url>
