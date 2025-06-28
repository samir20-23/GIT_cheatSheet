
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



<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=40&duration=4&pause=20&color=6D26BFFF&center=true&vCenter=true&width=482&lines=Git+Bash" alt="Samir Aoulad Amar" />
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=40&duration=4&pause=20&color=0D16BFFF&center=true&vCenter=true&width=482&lines=Git+Bash" alt="Samir Aoulad Amar" />
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=40&duration=4&pause=20&color=9D09BFFF&center=true&vCenter=true&width=482&lines=Git+Bash" alt="Samir Aoulad Amar" />


### **Git Bash**, here’s a quick guide with the most useful commands for navigation, file editing, and Git.  
---

## **🔥 Basic Navigation Commands**  
| Action | Command |
|--------|---------|
| **Check current folder** | `pwd` |
| **List files** | `ls` |
| **Go into a folder** | `cd foldername` |
| **Go back (up one level)** | `cd ..` |
| **Go to home folder** | `cd ~` |
| **Clear screen** | `clear` |

---

## **📂 File Management**  
| Action | Command |
|--------|---------|
| **Create a file** | `touch filename.php` |
| **Open & edit file** | `nano filename.php` |
| **Copy a file** | `cp oldfile.php newfile.php` |
| **Move/Rename file** | `mv oldname.php newname.php` |
| **Delete a file** | `rm filename.php` |
| **Create a folder** | `mkdir newfolder` |
| **Delete a folder** | `rm -r foldername` |

---

## **📋 Copy & Paste in Git Bash**  
| Action | Shortcut |
|--------|----------|
| **Copy from terminal** | `CTRL + SHIFT + C` |
| **Paste into terminal** | `CTRL + SHIFT + V` |

---

## **🔄 Switch Between Files & Folders**  
| Action | Command |
|--------|---------|
| **Go into a folder** | `cd foldername` |
| **List files** | `ls` |
| **Open a file in Nano** | `nano filename.php` |
| **Switch between opened files in Nano** | `CTRL + R`, then select file |

---

## **🚀 Git Commands**  
| Action | Command |
|--------|---------|
| **Clone a repo** | `git clone https://github.com/user/repo.git` |
| **Check repo status** | `git status` |
| **Add all changes** | `git add .` |
| **Commit changes** | `git commit -m "your message"` |
| **Push changes** | `git push origin main` |
| **Pull latest updates** | `git pull origin main` |
 

------------------------ 
```markdown
# Fix SSH Permission Denied Error When Pushing to GitHub

If you get the error:

```

[git@github.com](mailto:git@github.com): Permission denied (publickey).
fatal: Could not read from remote repository.

````

follow these steps to fix it:

---

## Steps to Fix SSH Permission Denied Error

1. **Generate a new SSH key (if you don't have one):**

```bash
ssh-keygen -t ed25519 -C "your-email@example.com"
````

Press Enter to accept defaults and optionally add a passphrase.

2. **Start the ssh-agent and add your key:**

On Windows PowerShell:

```powershell
Set-Service ssh-agent -StartupType Automatic
Start-Service ssh-agent
ssh-add $env:USERPROFILE\.ssh\id_ed25519
```

3. **Copy your public key to clipboard:**

```powershell
Get-Content $env:USERPROFILE\.ssh\id_ed25519.pub | clip
```

4. **Add the public SSH key to your GitHub account:**

* Go to: [https://github.com/settings/ssh/new](https://github.com/settings/ssh/new)
* Paste the key from clipboard into the **Key** field.
* Give it a title (e.g., "My PC") and save.

5. **Test the SSH connection:**

```bash
ssh -T git@github.com
```

You should see:

```
Hi username! You've successfully authenticated, but GitHub does not provide shell access.
```

6. **Now you can push your code using SSH:**

```bash
git remote set-url origin git@github.com:yourusername/yourrepo.git
git push origin main --force
```

---  
```
