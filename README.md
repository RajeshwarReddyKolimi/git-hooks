# git-hooks

- Used Post commit hook to print "Commit created"
## Steps followed

- Created a remote repository in github with a readme file.
- Cloned the repository to local.
- Added a new readme file name "commit-log.md".
- Navigated to .git/hooks folder and created "post-commit" script.
- Added the script which will log "Commit details added to commit-log.md" when the commit is completed and the details can be seen in commit-log.md.
- Added the executable permission to "post-commit" using `chmod +x post-commit`.
- Added commit-log.md to staging.
- Committed.
- Pushed the changed to remote repository.