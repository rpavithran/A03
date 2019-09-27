# A03

In order to use **GIT** and **GITHUB**, you must first create a new project, or a **repository**. In order to do this, you can take a local directory, or **clone** an existing Git repository. 
To keep track of what changes you have made, or to essentially save your new changes, you must make a **commit**. They allow you to go back to previous versions of your project, if necessary.
To transfer commits and upload local repository content to a **remote** repository, you use the **git push** command. It goes along with the **git fetch** command, which downoads commits and files from a remote repository into a local repository. 
The **git pull** fetches and downloads content from a remote repo and immediately updates the local repo to match that content. 
A **branch** separates development work without affecting other branches. Each repository has one branch, but can have many other branches that can be merged using a pull request. 
The git pull command is a combination of two commands, git fetch, followed by **git merge**, which takes independent lines created by git branch and integrates them into a single branch. 
If two branches change the same part of the same file and are merging together, Git won't be able to identify which version to use, so it stops right before the merge commit so that the user can resolve it manually. This is called a **merge conflict**, and can be solved with the git status command, which shows you which files need to be resolved.   

# Resources:

https://www.atlassian.com/git/tutorials/syncing/git-push
https://www.atlassian.com/git/tutorials/syncing/git-pull
https://www.atlassian.com/git/tutorials/using-branches/git-merge
https://help.github.com/en/articles/about-branches
https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners
