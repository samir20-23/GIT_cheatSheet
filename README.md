
<div id="header" align="center">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExenFvcHU1OGx6MDdiNzU1ZDlwajhld2YxbWdpNW8xMmRoZ2NoZ3BtZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/kH6CqYiquZawmU1HI6/giphy.webp" width="480"/>
       </a>
  
<div id="badges"  align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=63CF15&lines=Keep+calm+and+git+commit!)](https://git.io/typing-svg)
  
  </div>
</div>
<div id="badges"  align="start">

# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=17&pause=1002&color=F78900&background=FF960003&random=true&width=391&height=29&lines=GIT+GUIDE;git+clone+git+add+git+commit+git+push+)](https://git.io/typing-svg)
</div>
 
---
## Clone 
```bash
git clone <repository_url>
```
## Add
```bash
git add <file_name>    # Stage a specific file
git add .              # Stage all changes in the current directory
```
## Status
Check the status of your working directory and staging area.
```bash
git status
```
## Commit
```bash
git commit -m "Your descriptive message here"
```
## Push
```bash
git push origin <branch_name>
```
## Pull
```bash
git pull origin <branch_name> #Fetch and merge changes from a remote repository.
```
## Branches
Manage branches in your repository.
```bash
git branch <branch_name>          # Create a new branch
git checkout <branch_name>        # Switch to an existing branch
git checkout -b <branch_name>     # Create and switch to a new branch
git branch                        # List local branches
git branch -r                     # List remote branches
git branch -a                     # List all branches (local + remote)
git branch -d <branch_name>       # Delete a local branch
git push origin --delete <branch_name>  # Delete a remote branch
```
## Remote
```bash
git remote add origin <url>           # Add a new remote repository
git remote -v                         # List remote repositories
git remote set-url origin <new_url>   # Change the URL of a remote repository
```
## Submodules
Work with submodules in your repository.
```bash
git submodule add <url> <dir>         # Add a submodule
git submodule init                    # Initialize submodules
git submodule update                  # Update submodules
git rm --cached <path>                # Remove a submodule
git submodule deinit <path>           # Deinitialize a submodule
rm -rf <path>                         # Delete submodule files
```
## History
View commit history.
```bash
git log                               # Show commit history
git log --oneline                     # Show condensed commit history
git log --graph --oneline             # Show a visual graph of commits
```
## Revert
Revert changes in your working directory or repository.
```bash
git checkout <file_name>              # Discard changes in a specific file
git reset --hard                      # Discard all changes in the working directory and index
```
## Stash
Temporarily store changes that are not ready to commit.
```bash
git stash                             # Stash changes
git stash list                        # List stashed changes
git stash apply                       # Apply the latest stash
git stash drop                        # Delete the latest stash
```
## Delete Local
Delete a local file or directory (non-Git command).
```bash
rm -rf <dir>                          # Remove a directory and its contents
```
## Additional Tips
### Show Changes
View differences between file versions.
```bash
git diff                              # Show unstaged changes
git diff --staged                     # Show staged changes
```
### Undo Last Commit
Undo the last commit without deleting changes.
```bash
git reset --soft HEAD~1
```
### Amend Last Commit
Modify the last commit message or add changes.
```bash
git commit --amend
```
### Tagging
Create and manage tags.
```bash
git tag <tag_name>                    # Create a tag
git tag                               # List tags
git push origin <tag_name>            # Push a specific tag
git push origin --tags                # Push all tags
```

 
<div id="badges"  align="start">

### [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=17&pause=1002&color=ff0000&background=FF960003&random=true&width=391&height=29&lines=__________+___________+_______+________)](https://git.io/typing-svg)
</div>
<div id="badges"  align="start">

# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=17&pause=1002&color=4500ff&background=FF960003&random=true&width=391&height=29&lines=GIT+LFS)](https://git.io/typing-svg)
</div>
<div id="badges"  align="start">

# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=17&pause=1002&color=2eff00&background=FF960003&random=true&width=391&height=29&lines=GIT+LFS+METHOD+for+Large+Files+mp4+pdf+zip)](https://git.io/typing-svg)
</div>
### GIT LFS  METHOD  for  Large Files (.mp4 , .pdf, .zip)

```
Follow these steps to track large `.mp4` and `.pdf` and `.zip` files with Git LFS.

```

---

**Bash script to run:**

```bash
# Initialize Git LFS in the repository
git lfs install

# Track .mp4 and .zip files with Git LFS
git lfs track "*.mp4"
git lfs track "*.zip"
git lfs track "*.pdf"

# Add .gitattributes to the staging area
git add .gitattributes

# Add all files to the staging area
git add .

# Commit the changes
git commit -m "Track .mp4 and .pdf and .zip files with Git LFS"

# Push the changes to the repository
git push origin branch_name
```

