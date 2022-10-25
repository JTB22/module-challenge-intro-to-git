## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
	Git is a software used for file version control, allowing teams to more effectively work together in a large scale.
2. What is the difference between Git and GitHub?
	Git is the software used on the machine for version control and Github is a website providing online access to Git repositories.
3. Why do we create a branch?
	Branches are used to allow changes to made without effect the main (default) branch and can be merged while allowing overview from the team.
4. What is the purpose of a Pull Request?
	Pull request are used when a branch is ready to be merged with the base branch, allowing for review and changes before its merged.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
	git checkout main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
	git fetch is downloading changes made to the remote repository to the local machine.
	git merge allows changes made to a branch be merged with another branch.
	git pull will fetch changes made remotely and then merge them locally with your work.
7. What is a merge conflict?
	A merge conflict happens when a merge is requested however there change made to the same line or the file is missing. This needs to be resolved for a merge can happen.
8. How do you resolve a merge conflict?
	A line change merge conflict can be resolved by finding conflicting file (git status), open in a editor, finding the conflict markers, and deciding how to handle the conflicting edits. 
	Removed file merge conflicts are resovled by using git status to find the conflicting files and use git add (filename) or git rm (filename) to either add or remove the file.	
