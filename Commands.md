# Git Commands

## 1. Initial Setup

### Create Directory
```bash
mkdir git-for-devops
```

Creates a new directory named `git-for-devops`.

### Navigate into Directory
```bash
cd git-for-devops/
```
Changes the current working directory to `git-for-devops`.

### Check Current Directory
```bash
pwd
```
Displays the current working directory path.

### List Files in Parent Directory
```bash
ls -lrt ..
```
Lists the files and directories in the parent directory in long format, sorted by modification time.

## 2. Git Configuration

### Set Git User Name
```bash
git config --global user.name "RaneSuraj"
```
Sets the global Git username to "RaneSuraj" for all repositories on the system.

### Set Git User Email
```bash
git config --global user.email "ranesuraj92@gmail.com"
```
Sets the global Git email address for all repositories on the system.

## 3. Initialize Git Repository

### Initialize a New Git Repository
```bash
git init
```
Initializes a new Git repository in the current directory.

### View Git Configuration
```bash
git config --list
```
Lists the current Git configuration settings.

## 4. Working with Files

### Create New Files
```bash
touch nibba.txt nibbi.txt
```
Creates two new empty files named `nibba.txt` and `nibbi.txt`.

### View Files in Directory
```bash
ls -al
```
Lists all files in the current directory, including hidden files, with detailed information.

### Remove File
```bash
rm nibbi.txt
```
Deletes the file `nibbi.txt` from the working directory.

## 5. Staging and Committing Changes

### Add Files to Staging Area
```bash
git add .
```
Stages all changes (new, modified, deleted files) for the next commit.

### Check Git Status
```bash
git status
```
Shows the current status of the working directory and staging area.

### Commit Changes
```bash
git commit -m "Commit message"
```
Records changes to the repository with a descriptive message. Example:
```bash
git commit -m "create files nibba.txt & nibbi.txt"
```

### Edit a File
```bash
vi nibba.txt
```
Opens `nibba.txt` for editing using the `vi` text editor.

### Restore Deleted File
```bash
git restore nibbi.txt
```
Restores the deleted file `nibbi.txt` from the last commit.

## 6. Viewing Logs

### View Git Log
```bash
git log
```
Displays the commit history with detailed information about each commit.

### View Git Log in One Line
```bash
git log --oneline
```
Displays the commit history with each commit shown in a single line.

## 7. Branching and Switching

### Create New Branch
```bash
git checkout -b dev
```
Creates and switches to a new branch named `dev`.

### Switch to Branch
```bash
git switch master
```
Switches to the `master` branch.

### List Branches
```bash
git branch
```
Lists all the branches in the repository, highlighting the current branch.

## 8. Miscellaneous

### Clear Terminal
```bash
clear
```
Clears the terminal screen.

### View Command History
```bash
history
```
Displays the list of previously executed commands.

## 9. Git Clonning

### clone repository
```bash
git clone https://github.com/LondheShubham153/git-for-devops.git
```
get remote repository on your local system

## 10. Manage set of tracked repositories

### Manage repositories
```bash
git remote -v

git remote set-url origin git@github.com:RaneSuraj/git-for-DevOps.git
```
show remote url of the repositories

## 11. push pull commands for managing code

### Pushing Changes
```bash
git push
```
push changes from local system to the remote repositories

### Pulling Changes
```bash
git pull
```
pulling changes from remote repositories to our local system
