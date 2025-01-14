# Git-Basic-Commands
## MAIN COMMANDS
### ``cd`` -> "Change Directory"
``cd {name of directory/folder}``<br/>
Used to move through folders

### ``ls`` -> "List"
Lists all folders and files in current location

### ``touch`` -> "Create new files"
``touch {file1 file2 file3}``<br/>
Used to create multiple files within current location

### ``mkdir`` -> "Make Directory"
``mkdir {name of directory/folder}``<br/>
Used to create a new folder

## BASIC GIT COMMANDS
### ``git add`` -> "Add all files changed to being pushed" 
``git add -A``<br/>
<b>OR</b><br/>
``git add {specific files}``<br/>
Used to specify which files are being added, to later be pushed

### ``git commit`` -> "Commit a message name for changes made"
``git commit -m "{Changes made}"``<br/>
<i><u>(Quotations required)</i></u><br/>
Used to explain the changes that have been made through the "git add" command

### ``git status`` -> "Check the status"
Check the current status. What files have been added/modified/deleted.

### ``git push`` -> "Push!"
Pushes the commit made to GitHub.com

## GIT BRANCH COMMANDS
### ``git branch`` -> "Get all the branches"
Used to list all the branches that the code currently has<br/>
``git branch -d {branch name}``<br/>
Used to delete the specific branch <br/>
<u>*NOTE*:</u> You can NOT be in the branch you are trying to delete!

### ``git checkout`` -> "Check out the branch"
``git checkout {branch name}``<br/>
Used to switch branches<br/>
``git checkout -b {branch name}``<br/>
Used to create a new branch, then switch into that branch

``git push origin {branch name}`` -> "Push that branch!"<br/>
Used to push a specific branch to GitHub.com

### ``git merge`` -> "Merge the branches."
``git merge {branch}``<br/>
Used to merge a branch into a different branch, or main<br/>
*<u>NOTE:</u>* Merges into the branch you are currently in

## PULLING FROM GITHUB
### ``git clone`` -> "Clone the GitHub Repo"
``git clone {repo https}``<br/>
Used to clone/create a copy of the GitHub.com Repository to the current folder you are in on your computer

### ``git log`` -> "Show me the logs."
Used to see a log of the previous commits made<br/>
*<u>NOTE:</u>* To leave the logs, push the "q" key