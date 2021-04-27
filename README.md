# Saturn

## Branching
it branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes.

$ git branch <new_branch_name>
	Creates a branch from current
$ git checkout -b <new_branch_name>
	Creates branch and 'checks out' to the new branch, which means it'll position you onto the new branch as it is created
$ git checkout <branch_name>
	Will set it to another branch
$ git branch -d <branch_name>
	Deletes a branch
$ git --delete origin <branch_