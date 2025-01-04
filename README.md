# LEARNING HOW TO USE GIT & GITHUB

## Basic Git Setup
```bash
$ git --version  # Check if Git is installed on your PC
$ git config --global color.ui auto
$ git config --global user.name "yourusername"
$ git config --global user.email "example@gmail.com"
```
Note:
Use --global to set the username and email for every repository on your computer.
If you want to set the username/email for just the current repo, you can remove --global.

## Creating a Repository
```bash
$ mkdir example  # Create a directory named example
$ cd example  # Change to the example directory
$ git init  # Initialize Git in the example folder and create a repository
$ rm -rf .git  # Delete/uninitialize a Git repository
```

## Creating Files

```bash
$ touch index.html  # Create index.html
$ touch script.js  # Create script.js
$ touch style.css  # Create style.css
```

## Viewing Files
```bash
$ ls  # List files in the current directory
# Output: index.html script.js style.css
```

## Staging and Unstaging Files
```bash
$ git add index.html  # Stage index.html
$ git rm --cached index.html  # Unstage index.html
$ git add .  # Stage all files in the directory
$ git add -A  # Same as above
$ git add --all  # Same as above
```

## Checking Status
```bash
$ git status  # View the status of your repository
```

## Removing Staged Files
```bash
$ git rm -r --cached .  # Unstage/remove all files in the directory
```

## Committing Changes
```bash
$ git commit -m "My commit message"  # Commit changes with a message
```

## Viewing Commit History
```bash
$ git log  # View the commit history for the repository
```

## Managing Branches
```bash
$ git branch -M branch_name  # Rename or create a branch
$ git branch -d branch_name  # Delete a branch
$ git branch  # List all branches
# Output: * master  # '*' indicates the current branch
          main
$ git checkout branch_name  # Switch to another branch
```

## Connecting to a Remote Repository
```bash
$ git remote add origin https://github.com/yourusername/example.git  # Add a remote repository
$ git push -u origin main  # Push changes to the main branch
```

## Other Useful Commands
```bash
$ git --help  # Display help information
$ ctrl + l  # Clear the terminal
$ git show  # Show information about the most recent commit
$ cd ..  # Navigate to the parent directory
$ dir  # List the contents of the directory (Windows)
$ git config  # View Git configuration
$ git config -l  # List all Git configuration
$ ls -a  # List all files, including hidden ones
$ git merge main  # Merge the main branch into the current branch
```
