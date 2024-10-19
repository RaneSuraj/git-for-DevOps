Git Commands

1. Initial Setup

Create Directory
    mkdir git-for-devops
    Creates a new directory named `git-for-devops`.

Navigate into Directory
    cd git-for-devops/
    Changes the current working directory to `git-for-devops`.

Check Current Directory
    pwd
    Displays the current working directory path.

List Files in Parent Directory
    ls -lrt ..
    Lists the files and directories in the parent directory in long format, sorted by modification time.

2. Git Configuration

Set Git User Name
    git config --global user.name "RaneSuraj"
    Sets the global Git username to "RaneSuraj" for all repositories on the system.

Set Git User Email
    git config --global user.email "ranesuraj92@gmail.com"
    Sets the global Git email address for all repositories on the system.

3. Initialize Git Repository

Initialize a New Git Repository
    git init
    Initializes a new Git repository in the current directory.

View Git Configuration
    git config --list
    Lists the current Git configuration settings.

4. Working with Files

Create New Files
    touch nibba.txt nibbi.txt
    Creates two new empty files named `nibba.txt` and `nibbi.txt`.

View Files in Directory
    ls -al
    Lists all files in the current directory, including hidden files, with detailed information.

Remove File
    rm nibbi.txt
    Deletes the file `nibbi.txt` from the working directory.

5. Staging and Committing Changes

Add Files to Staging Area
    git add .
    Stages all changes (new, modified, deleted files) for the next commit.

Check Git Status
    git status
    Shows the current status of the working directory and staging area.

Commit Changes
    git commit -m "Commit message"
    Records changes to the repository with a descriptive message. Example:
    git commit -m "create files nibba.txt & nibbi.txt"

Edit a File
    vi nibba.txt
    Opens `nibba.txt` for editing using the `vi` text editor.

Restore Deleted File
    git restore nibbi.txt
    Restores the deleted file `nibbi.txt` from the last commit.

6. Viewing Logs

View Git Log
    git log
    Displays the commit history with detailed information about each commit.

View Git Log in One Line
    git log --oneline
    Displays the commit history with each commit shown in a single line.

7. Branching and Switching

Create New Branch
    git checkout -b dev
    Creates and switches to a new branch named `dev`.

Switch to Branch
    git switch master
    Switches to the `master` branch.

List Branches
    git branch
    Lists all the branches in the repository, highlighting the current branch.

8. Miscellaneous

Clear Terminal
    clear
    Clears the terminal screen.

View Command History
    history
    Displays the list of previously executed commands.
