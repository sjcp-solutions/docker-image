# Base Docker Image

## Gitlab Repository Settings
### Push Rule
Set the following rules:
* Do not allow users to remove git tags with git push
* Prevent committing secrets to Git
* Commit author's email: `@sjcp-solutions.com`

### Push to a remote repository
Create a personal token on Git Hub for mirroring the repository

Add a build step to the Gitlab pipeline to push to Github. Use the personal token for the password.

