# MSSE640
1. Git is a distributed version control system, meaning that it allows developers to work on their local copies of a project, while still enabling them to push changes to a shared repository.

2. Snapshots in git save the state of the entire git workspace, not just individual files. When you commit changes in Git, you are essentially saving a snapshot of your project.

3. A local repository resides on a user's local machine. It acts the same as a remote repo, meaning you can perform commits, branching, merging, etc. The main difference between the two is that a remote repo is hosted on a server accessible over the internet, and it allows multiple developers to collaborate on the same project. A local repository can actually commit, branch, merge, and push changes to remote repositories by setting an HTTPS link between the two.

4. A commit records changes made to the files in a repository and essentially represents a snapshot of your repository at a specific point in time.

5. The working directory is another phrase for your project folder. This is where all of your project files reside in your local machine and where you make all of your changes before they are staged and committed to the repository.

6. The staging area is an intermediate space where you can format and review commits before finalizing them. When you "git add" a file that you edit, you're basically sending it to the "staging area" before committing changes.

7. Git workflow:

    Local                                                                 | Remote
----------------------------------------------------------------------------------------------
Working dir. --git add--> Staging Area --git committ--> local repo --git push--> remote repo

                         Working dir  <--git checkout-- local repo <--git pull-- remote repo
