## Git 

Impressions about materials

### Branching 

Move to new branch than you working on new *task/feature*. 


## Cheatsheet

` git checkout -b new_branch_name `

*-b* - stands for creating new branch.

` git branch -d branch_name `

*-b* - stands for deleting branch.

This command deletes only branch, not commits.

` git merge branch1 branch2 ` 

Merge branch2 to branch1.

` git show commit_id `

Compare commit to its parent

## (NEW!) Newline characters between Windows and Unix systems

*Context*: Whenever we hit the "Enter" key on the keyboard, we are actually telling the computer to insert an invisible character into our text file to indicate to the computer that there should be a new line. *Unix* systems adds one character called the "line feed" character or LF or \n while *Windows* systems adds two characters, "carriage return" and "line feed" or CRLF or \r\n.

Solution for merge conflict if you working on Widows.

`git config --global core.autocrlf true`

## (SURPRISED!)

## (USE IN THE FUTURE!)
