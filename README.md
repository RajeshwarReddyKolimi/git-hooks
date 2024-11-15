# git-hooks

- Used Post commit hook to print "Commit created"
## Steps followed

- Created a remote repository in github with a readme file.
- Cloned the repository to local.
- Added a new readme file name "commit-log.md".
- Navigated to .git/hooks folder and created "post-commit" script.
- Added the script `echo "Commit created"` which will log "Commit created" when the commit is completed.
- Added the executable permission to "post-commit" using `chmod +x post-commit`.
- Added commit-log.md to staging.
- Committed.
- Pushed the changed to remote repository.