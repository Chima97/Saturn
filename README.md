<<<<<<< HEAD
# Branching
it branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes.

1. git branch <new_branch_name>
	Creates a branch from current
	
2. git checkout -b <new_branch_name>
	Creates branch and 'checks out' to the new branch, which means it'll position you onto the new branch as it is created
	
3. git checkout <branch_name>
	Will set it to another branch
	
4. git branch -d <branch_name>
	Deletes a branch
	
5. git --delete origin <branch_name>
	Deletes the branch from develop
	
Once you have made your branch you must push it for it to be shown on your repository.
$ git push

If you have created files within your branch, you will need to commit these files before you push your branch

=======
# Saturn

*This is the recommended workflow process for making changes throughout a project's lifecycle.*

### Follow these steps

1. Make a new feature branch
2. Switch to the new feature branch
3. Make changes
4. Stage changes
5. Commit changes
6. Push changes
7. If more changes are needed for your current feature branch, restart at Step 3
8. Switch back to develop branch
9. Once no more changes are required, merge those changes into develop branch
10. Delete feature branch if necessary
>>>>>>> 668862bc4c67a846c13bb192820f76b47e8d7cda
