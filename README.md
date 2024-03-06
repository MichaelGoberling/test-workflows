# test-workflows
Repo for testing different aspects of GitHub Workflows

## Tests

- conditional-environment.yml - I have the same workflow file for both stage and prod, but want to set the `environment` key based on if there's a commit to main (stage) or if there's a new release (prod)
