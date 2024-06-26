
### Basic Commands

1. **Initialize a repository:**
   ```sh
   git init
   ```

2. **Clone a repository:**
   ```sh
   git clone <repository_url>
   ```

3. **Check the status:**
   ```sh
   git status
   ```

4. **Add files to staging:**
   ```sh
   git add <file_or_directory>
   ```

5. **Commit changes:**
   ```sh
   git commit -m "commit message"
   ```
### Branching and Merging

6. **Create a new branch:**
   ```sh
   git branch <branch_name>
   ```

7. **Switch to a branch:**
   ```sh
   git checkout <branch_name>
   ```

8. **Create and switch to a new branch:**
   ```sh
   git checkout -b <branch_name>
   ```

9. **Merge a branch:**
   ```sh
   git merge <branch_name>
   ```

### Remote Repositories

10. **Add a remote repository:**
    ```sh
    git remote add <remote_name> <repository_url>
    ```

11. **Fetch changes from a remote:**
    ```sh
    git fetch <remote_name>
    ```
12. **Pull changes from a remote:**
    ```sh
    git pull <remote_name> <branch_name>
    ```

13. **Push changes to a remote:**
    ```sh
    git push <remote_name> <branch_name>
    ```
    
### Undoing Changes

14. **Discard local changes:**
    ```sh
    git checkout -- <file>
    ```

15. **Reset to a previous commit:**
    ```sh
    git reset --hard <commit_hash>
    ```

16. **Revert a commit:**
    ```sh
    git revert <commit_hash>
    ```

### Viewing History

17. **Show commit history:**
    ```sh
    git log
    ```
   
18. **Show changes:**
    ```sh
    git diff
    ```

19. **Show a specific commit:**
    ```sh
    git show <commit_hash>
    ```

### Tagging

20. **Create a tag:**
    ```sh
    git tag <tag_name>
    ```

21. **Push tags to remote:**
    ```sh
    git push <remote_name> <tag_name>
    ```

### Configuration

22. **Set user name:**
    ```sh
    git config --global user.name "Your Name"
    ```

23. **Set user email:**
    ```sh
    git config --global user.email "your.email@example.com"
    ```
