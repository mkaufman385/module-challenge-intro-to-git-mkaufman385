## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
	Git is a free and open source version control system built to handle different sized 	projects with speed and efficiency.
2. What is the difference between Git and GitHub?
	Git is a tool that is used to handle multiple versions of source code edits which are 	transferred to files in a Git repository and Github serves as a location for 	uploading copies of a Git repository.
3. Why do we create a branch?
	Branches are created in Git because when you add a new feature or fix a bug, 	regardless of size, you create a new branch to enclose your changes.
4. What is the purpose of a Pull Request?
	A pull request allows you to notify your team that you have work that needs 	reviewing. 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
	git switch main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
	-Git fetch pulls in all the commits from your remote but does not make changes to 	your local files.
	-Git merge lets you take the individual lines created by a git branch and integrate 	them into a single branch.
	-Git pull is used to update the local version of a repository from a remote. 
	-Git pull fetches (git fetch) the new commits and merges (git merge) these into your 	local branch.
7. What is a merge conflict?
	A merge conflict occurs when Git cannot automatically resolve code differences 	between two commits.
8. How do you resolve a merge conflict?
	To resolve a merge conflict, open it and make any necessary changes. Once this is 	done, we can use the 'git add' command. Then create a new commit with the 'git 	commit' command. Git will create a new merge commit to finalize the merge. 
