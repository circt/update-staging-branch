# Update Staging Branch

Composite GitHub action that updates a staging branch.  This staging branch is
part of the CI/CD flow where a downstream project is kept up-to-date with
`llvm/circt`.

# Usage

```yaml
- name: Update Staging Branch
  uses: circt/update-staging-branch@test
  with:
    # The name that will be associated with any created commits
    user: ''

    # The email address that will be associated with any created commits
    email: ''

    # The name of the default branch
    #
    # Default: 'main'
    main-branch: ''

    # The name of the staging branch
    #
    # Default: 'ci/ci-circt-nightly'
    staging-branch: ''
```
