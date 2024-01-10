# Git and GitHub Commands

Here is a list of common Git and GitHub commands along with a brief description of each:

## Basic Git Commands:

1. **git init:**
    - Initializes a new Git repository in the current directory.

    ```bash
    git init
    ```

2. **git clone:**
    - Creates a copy of a remote repository on your local machine.

    ```bash
    git clone https://github.com/repository.git
    ```

3. **git add:**
    - Adds changes in the working directory to the staging area.

    ```bash
    git add file.txt
    ```

4. **git commit:**
    - Records changes from the staging area to the repository.

    ```bash
    git commit -m "Your commit message"
    ```

5. **git status:**
    - Displays the status of changes as untracked, modified, or staged.

    ```bash
    git status
    ```

6. **git diff:**
    - Shows changes between the working directory and the last commit.

    ```bash
    git diff
    ```

## Branching and Merging:

7. **git branch:**
    - Lists existing branches or creates a new branch.

    ```bash
    git branch
    git branch feature-branch
    ```

8. **git checkout:**
    - Switches to a specified branch.

    ```bash
    git checkout feature-branch
    ```

9. **git merge:**
    - Combines changes from one branch into another.

    ```bash
    git merge feature-branch
    ```

## Remote Repositories:

10. **git remote:**
     - Lists remote repositories.

     ```bash
     git remote -v
     ```

11. **git fetch:**
     - Downloads changes from a remote repository without merging.

     ```bash
     git fetch origin
     ```

12. **git pull:**
     - Fetches changes from a remote repository and merges them into the current branch.

     ```bash
     git pull origin main
     ```

13. **git push:**
     - Pushes local changes to a remote repository.

     ```bash
     git push origin main
     ```

## Advanced Commands:

14. **git log:**
     - Displays a log of commits.

     ```bash
     git log
     ```

15. **git reset:**
     - Resets the working directory to a specified commit.

     ```bash
     git reset --hard commit-hash
     ```

16. **git stash:**
     - Temporarily saves changes that are not ready to be committed.

     ```bash
     git stash
     ```

17. **git tag:**
     - Creates, lists, or deletes tags.

     ```bash
     git tag -a v1.0 -m "Release 1.0"
     ```
