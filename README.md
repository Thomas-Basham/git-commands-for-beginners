# Git Commands For Beginners


## Need to Know



| Command                                            | Description                                                                                                             |
| ---------------------------------------------------| -----------------------------------------------------------------------------------------------------------------------|
| `git status`                                       | Display the current state of the repository, including which files are staged or unstaged                                |
| `git add <file>`                                   | Stage a file for commit                                                                                                 |
| `git add .`                                        | Stage all changes (including untracked files) for commit                                                               |
| `git commit -m "<message>"`                        | Commit staged changes with a descriptive message                                                                        |
| `git push origin <branch>`                         | Push local commits to a remote repository on the specified branch                                                        |
| `git clone <url>`                                  | Clone a remote repository to your local machine                                                                        |
| `git init`                                         | Initialize a new Git repository                                                                                        |
| `git remote add origin <url>`                      | Add a new remote repository to the list of remotes                                                                      |
| `git checkout <branch-name>`                       | Switch to an existing branch                                                                                            |
| `git checkout -b <branch-name>`                    | Create a new branch and switch to it                                                                                    |
| `git pull origin <branch>`                         | Fetch changes from a remote repository and merge them into the current branch                                            |
| `git branch`                                       | List all branches in the repository                                                                                     |


## Other useful Commands

| Command                                            | Description                                                                                                             |
| ---------------------------------------------------| -----------------------------------------------------------------------------------------------------------------------|
| `git log`                                          | Show the commit history of the current branch                                                                           |
| `git reset <file>` or `git reset --hard`           | Reset the specified file or the entire working directory to the state of the most recent commit                          |
| `git diff`                                         | Show the difference between the working directory and the most recent commit                                             |
| `git stash`                                        | Temporarily stash changes in the working directory so that they can be retrieved later                                    |
| `git stash apply` or `git stash pop`               | Retrieve stashed changes and apply them to the working directory                                                         |
| `git rm <file>` or `git rm --cached <file>`        | Remove a file from the repository and stage the deletion for commit                                                      |
| `git merge <branch-name>`                          | Merge the specified branch into the current branch                                                                      |
