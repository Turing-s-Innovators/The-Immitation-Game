### The Immitation Game

# Git Workflow
 1. Create new branch
    `git checkout -b <name of branch>`
 2. ∆ code to complete ticket
 3. `git status`
 4. `git add < . . . >`
 5. `git commit`
 6. `git push origin <branch I'm pushing to remote>`
 7. `git checkout main`
 8. `git pull origin main`
 9. `git checkout <branch name>`
 10. `git merge main`
 11. `git push origin <branch name>`
 12. Pull request

Getting started:
Copy config_example copy.js and rename config.js.  Edit config.js to include your personal tokens.
```
NPM install
```
```
NPM install react-image-magnify --force
```
forced install is required due to reliance on early version of react

This product utilizes redis which will need to be installed separately.  Installation instructions are located at https://redis.io/docs/getting-started/.  Once installed, ensure redis is running.
```
NPM run build
```
```
NPM run server-dev
```
