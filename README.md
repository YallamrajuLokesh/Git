# GIT NOTES 
```bash
# Change Directory
cd C:\Users\Admin\Desktop\LearnGit
# Navigates to the specified directory.



# List Directory Contents

dir

# Displays files and directories in the current directory.

# Create Multiple Directories
mkdir gitone gittwo gitthree
# Creates three directories named gitone, gittwo, and gitthree.

# Check Git Version
git --version
# Displays the installed version of Git.

# List Directory Contents Again
dir
# Shows the contents of the current directory.

# Check Git Status
git status
# Shows the state of the working directory and staging area.

# Change Directory to gitone
cd gitone
# Navigates into the gitone directory.

# Initialize a New Git Repository
git init
# Initializes a new Git repository in the current directory.

# Check Git Status Again
git status
# Shows the state of the repository after initialization.

# Add All Files to Staging Area
git add .
# Adds all changes in the current directory to the staging area.

# Commit Changes
git commit -m "add file one"
# Records changes made to the files in the repository with a message.

# Set User Name
git config user.name "Lokesh"
# Configures the name to be associated with commits.

# Set User Email
git config user.email "lokeshthor778@gmail.com"
# Configures the email to be associated with commits.

# Check Current Branch
git branch
# Lists all branches in the repository, highlighting the current branch.

# Rename Current Branch
git branch -M main
# Renames the current branch to 'main'.

# Check Remote Repositories
git remote -v
# Displays the remote repositories associated with the local repository.

# Add Remote Repository
git remote add origin https://github.com/YallamrajuLokesh/Git.git
# Links the local repository to a remote repository on GitHub.

# Push Changes to Remote Repository
git push -u origin main
# Pushes changes from the local repository to the remote repository, setting upstream tracking.

# Add Changes Again
git add .
# Adds all changes in the current directory to the staging area.

# Check Git Status Again
git status
# Shows the state of the repository, indicating changes to be committed.

# Add a Specific File to Staging Area
git add 3.txt
# Adds the specified file to the staging area.

# Commit Changes Again
git commit -m "new"
# Records the changes made to the files in the repository with a message.

# Push Changes Again
git push
# Pushes committed changes to the remote repository.
