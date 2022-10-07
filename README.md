## Development Instructions

- Before starting any local develpment, fetch from the remote `main` branch to make sure your local `main` branch is updated. If there changes, pull them.
```
git checkout main
```
```
git fetch
```
```
git pull
```
- When an issue is created, checkout to a new local branch against that issue (including issue number at the start of the branch name), and then start development.
```
git checkout -b your-branch-name
```
- Test your changes. If the changes pass tests, make a new commit with a message describing the change in short and starting with the issue number in [].
```
git commit -m '[issue number] your commit message'
```
- Push your new branch to remote.
```
git push origin your-branch-name
```
- Once the push is complete, create a pull request and assign a reviewer to review and approve your code before merging to the `main` branch.
