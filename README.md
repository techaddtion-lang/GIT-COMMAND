| Command                     | Meaning                        | Example                             |
| --------------------------- | ------------------------------ | ----------------------------------- |
| `git init`                  | Start Git                      | `git init`                           |
| `git status`                | Check changes                  | `git status`                        |
| `git add .`                 | Stage all changes              | `git add .`                         |
| `git add file`              | Stage one file                 | `git add app/page.tsx`              |
| `git commit -m "message"`   | Save changes                   | `git commit -m "add search"`        |
| `git push`                  | Upload to GitHub               | `git push`                          |
| `git pull`                  | Download latest changes        | `git pull`                          |
| `git clone URL`             | Download repository            | `git clone URL`                     |
| `git branch`                | Show branches                  | `git branch`                        |
| `git switch branch`         | Change branch                  | `git switch main`                   |
| `git switch -c name`        | Create + switch branch         | `git switch -c feature`             |
| `git merge branch`          | Merge branch                   | `git merge feature`                 |
| `git log --oneline`         | Show commits                   | `git log --oneline`                 |
| `git remote -v`             | Show GitHub connection         | `git remote -v`                     |
| `git rm file`               | **Remove file**                | `git rm app/test.js`                |
| `git rm -r folder`          | **Remove folder**              | `git rm -r oldFolder`               |
| `git mv old new`            | Rename file                    | `git mv old.js new.js`              |
| `git restore file`          | Undo file changes              | `git restore app/page.tsx`          |
| `git restore --staged file` | Remove file from staging       | `git restore --staged app/page.tsx` |
| `git reset --soft HEAD~1`   | Undo last commit, keep changes | `git reset --soft HEAD~1`           |
| `git remote remove origin`  | Remove GitHub connection       | `git remote remove origin`          |
| `git push --force`          | Force upload/overwrite remote  | `git push --force`                  |
 


NEW PROJECT:
git init
git add .
git commit -m "initial commit"
git remote add origin URL
git push -u origin main

git add .
    ↓
git commit -m "what you changed"
    ↓
git push


git rm app/test.js
git commit -m "remove test file"
git push

git rm -r oldFolder
git commit -m "remove old folder"
git push
