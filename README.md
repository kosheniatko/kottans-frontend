## Git and GitHub
---
*VCS* - Version Control System.

#### Installing on Linux (Ubuntu OS)

`sudo apt-get install git`

GUI for git -> GitHub Desktop

#### Config base parameters

```
git config --global user.name "My Name"
git config --global user.email myEmail@example.com
```
#### Staging area

Modified files in current version for nex **commit**

### Branching 

Move to new branch than you working on new *task/feature*. 

## Cheatsheet
---
`git init`

Initialiaze of new git repository.

`git status`

Displays the state of the working directory/staging area.

`git add file_name`

Add modified file to the staging area.

`git add -A` or `git add .`

Add all files to the staging area.

`git commit -m "Commit message"` 

Create commit. *-m* stands for *message*

Add all files to the staging area.

` git checkout -b new_branch_name `

*-b* - stands for creating new branch.

` git branch -d branch_name `

*-d* - stands for deleting branch.

This command deletes only branch, not commits.

` git merge branch1 branch2 ` 

Merge branch2 to branch1.

` git show commit_id `

Compare commit to its parent

`git remote add origin https://remote.repo`

Linking local repo to remote.

`git push`

Upload local changes to remote repo.

`git clone`

Clone remote *repo* to local.

`git pull`

Get changes from remote repository.

`git log`

Show list of all commits

`git diff commit1 commit2`

Show differancy between two commits


## (NEW!) Newline characters between Windows and Unix systems

*Context*: Whenever we hit the "Enter" key on the keyboard, we are actually telling the computer to insert an invisible character into our text file to indicate to the computer that there should be a new line. *Unix* systems adds one character called the "line feed" character or LF or \n while *Windows* systems adds two characters, "carriage return" and "line feed" or CRLF or \r\n.

Solution for merge conflict if you working on Windows.

`git config --global core.autocrlf true`

## (SURPRISED!)

## (USE IN THE FUTURE!)

I'll use in the future Git and GitHub :heart: It's very helpful for monitoring my own projects for any activity.

#### .gitignore

Ignored files are usually build artifacts and machine generated files that can be derived from your repository source or should otherwise not be committed. Some common examples are:

1. dependency caches, such as the contents of /node_modules or /packages
2. compiled code, such as .o, .pyc, and .class files
3. build output directories, such as /bin, /out, or /target
4. files generated at runtime, such as .log, .lock, or .tmp
5. hidden system files, such as .DS_Store or Thumbs.db
6. personal IDE config files, such as .idea/workspace.xml