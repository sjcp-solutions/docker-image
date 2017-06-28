# Base Docker Image

## Gitlab Repository Settings
### Push Rule
Set the following rules:
* Do not allow users to remove git tags with git push
* Check whether author is a GitLab user
* Prevent committing secrets to Git
* Commit author's email: `@sjcp-solutions.com`

### Push to a remote repository
Create a personal token on Git Hub for mirroring the repository

Use the token for the password to mirror the repoistory between gitlab and github.