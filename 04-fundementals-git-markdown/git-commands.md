# Git Commands

## 1. `git init`
The `git init` command initializes a new Git repository in the current directory. It sets up all the necessary files and folders that Git needs to start tracking changes in a project.

## 2. `git clone`
The `git clone` command creates a copy of an existing Git repository from a remote source to the local machine. It also automatically sets up the remote connection to the original repository.

## 3. `git add .`
The `git add .` command stages all the changes (new files, modified files, and deleted files) in the current directory and its subdirectories for the next commit. The period (.) refers to the current directory.

## 4. `git commit -m "message"`
The `git commit` command records the staged changes (from git add) in the local repository. The `-m "message"` flag allows us to add a short, descriptive message about the changes we've made, which will be stored with the commit.

## 5. `git push origin master`
The `git push` command uploads the local repository changes to a remote repository. The `origin` refers to the default name of the remote repository, and `master` refers to the main branch.

## 6. `git status`
The `git status` command shows the current state of the working directory and staging area. It displays which changes have been staged, which files are not being tracked, and if there are any files with changes that haven't been committed yet.

## 7. `git remote add origin`
The `git remote add origin` command adds a remote repository URL to the local repository. This is typically used when we want to link our local project to a remote repository.

## 8. `git remote remove origin`
The `git remote remove origin` command removes a remote connection from the local repository. This is useful if we want to disconnect from the remote repository.

## 9. `git remote -v`
The `git remote -v` command displays the remote repositories linked to the local project, along with their fetch and push URLs. It is helpful to check which remote repositories our project is connected to.

## 10. `git reset`
The `git reset` command is used to undo changes. It can be used in different ways, depending on the option used:

- `git reset HEAD`: Unstages changes that were added with git add but keeps them in the working directory.
- `git reset --hard`: Resets the working directory and staging area to a specific commit, removing all uncommitted changes.

## 11. `git log`
The `git log` command shows a list of all the commits in the current branch. Each commit is displayed with details like the author, date, and commit message.

