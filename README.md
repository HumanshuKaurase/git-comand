# Git Commands

##  Initialization
- **Create a new Git repository**:
  
  `git init`

##  Configuration
- **Set global username**:
  
  `git config --global user.name "Naruto"`

- **Set global email**:
  
  `git config --global user.email "narutouzumaki@gmail.com"`

##  File Operations
- **Create a new file**:
  
  `touch <filename>`

- **Remove a file**:
  
  `rm <filename>`

- **Restore a deleted file**:
  
  `git restore <filename>`

##  Staging and Commit
- **Check the status of the repository**:
  
  `git status`

- **Add a file to the staging area**:
  
  `git add <filename>`

- **Commit changes with a message**:
  
  `git commit -m "your commit message"`

##  Branching
- **Create a new branch**:
  
  `git checkout -b <branch_name>`

- **Switch between branches**:
  
  `git checkout <branch_name>`

- **List all branches**:
  
  `git branch`

##  Logs
- **View commit history**:
  
  `git log`

- **View concise commit history**:
  
  `git log --oneline`

##  Remove from Staging
- **Unstage a file (remove from index but keep in working directory)**:
  
  `git rm --cached <filename>`

##  Miscellaneous
- **View all files, including hidden ones**:
  
  `ls -a`

- **Clear terminal screen**:
  
  `clear`

- **View command history**:
  
  `history`
