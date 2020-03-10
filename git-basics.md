# Git basics

Git is a VCS(Version Control System), it basically enables you to work on a project(code base) alongside with others in a controlled way.

## Most common Git commands

1. `git init` : Creates an empty git repository in a folder, this will let you version/keep track of changes in that directory.
2. `git clone https://github.com/example/repository` : Clones/downloads a repository from a Git Server(Github, Gitlab, Bitbucket, etc.)
3. `git add *` : Add all files to Git so that they are tracked/versioned/saved
4. `git commit -m "Add a new file"` : Commits the `add`-ed files and adds a commit message
5. `git push origin master` : Push the changes you made locally to the Git server
6. `git remote add origin <git-server>` : Adds/connect to a remote Git server(Gitlab, Github etc.)
7. `git branch` : List the current branch
8. `git branch test` : Creates a new branch named `test`
9. `git checkout test` : Switches to the new branch named `test`
10. `git checkout master` : Switch back to the default `master` branch
11. `git branch -d test` : Delete the `test` branch
12. `git checkout -b test` : Create the test branch and checkout/switch on it
13. `git status` : Check the current status of your repository
14. `git pull` : Pull/Update the current local repository with the remote Git server, so that we are in sync
15. `git log` : Show history of all of our changes
16. `gitk` : More graphic way of seeing Git changes
17. `git diff` : See "differences" in the repository or between branches/files


Useful links:
  * https://rogerdudler.github.io/git-guide/
  * https://www.atlassian.com/git
  
  
