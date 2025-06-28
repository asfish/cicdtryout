Here’s a cleaned up and better-formatted version of your README.md. I’ve improved headings, code blocks, and bullet formatting for readability:

```markdown
# Git Commands and Notes

## Configuring Git

After installing Git, you should configure your username and email address—these will be attached to all your commits.

```sh
git config --global user.name "your-username"
git config --global user.email "your-email"
```

Learn more: [Git Configuration Options](https://git-scm.com/docs/git-config)

---

## Common Git Commands

- Initialize a local repository:
  ```sh
  git init
  ```
- Stage a file for the next commit:
  ```sh
  git add <file_name>
  ```
- Create a new branch:
  ```sh
  git branch <branch-name>
  ```
- Create and switch to a new branch:
  ```sh
  git checkout -b <branch-name>
  ```
- List all branches:
  ```sh
  git branch
  ```
- Switch between branches or commits:
  ```sh
  git checkout <branch-name>
  ```
- Delete a branch permanently:
  ```sh
  git branch -D <branch-name>
  ```
- Merge a branch into the current branch:
  ```sh
  git merge <branch-name>
  ```
- Add a remote repository:
  ```sh
  git remote add origin <url-to-remote-repo>
  ```
- Push a branch to origin:
  ```sh
  git push origin <branch-name>
  ```
- Set or update the remote repository URL:
  ```sh
  git remote set-url origin https://user-name@<url.git>
  ```
- Pull a branch from origin:
  ```sh
  git pull origin <branch-name>
  ```
- List remote aliases:
  ```sh
  git remote
  ```
- Show the URL for the remote repo:
  ```sh
  git remote get-url origin
  ```

---

## Undoing Commits

- Revert a commit (keeps history):
  ```sh
  git revert <id>
  ```
- Reset to a commit (removes history):
  ```sh
  git reset <id>
  ```
```

Let me know if you want any additional formatting or information added!