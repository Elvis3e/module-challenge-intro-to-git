## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
While Git is a tool that's used to manage multiple versions of source code edits that are then transferred to files in a Git repository
2. What is the difference between Git and GitHub?
While Git is a tool that's used to manage multiple versions of source code edits that are then transferred to files in a Git repository, GitHub serves as a location for uploading copies of a Git repository
3. Why do we create a branch?
When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes.
4. What is the purpose of a Pull Request?
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout -b
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch fetches updates but does not merge them. git pull does a git fetch under the hood and then a merge . git fetch is similar to pull but doesn't merge.
When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them.
The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content
7. What is a merge conflict?
That means that two of your commits modified the same line in the same file, and Git doesn't know which change to apply.
8. How do you resolve a merge conflict?
To fix the conflict, you can follow the standard procedures for resolving merge conflicts from the command line. When you're finished, you'll need to call git rebase --continue in order for Git to continue processing the rest of the rebase.
