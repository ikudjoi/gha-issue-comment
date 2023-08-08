# gha-issue-comment

Composite GitHub action that comments on an issue or pull request using actions/github-script action.

Requires the pull-requests and/OR issues write permission to your workflow:

```yaml
permissions:
  pull-requests: write
  issues: write
```

# usage

```yaml
  - uses: ikudjoi/gha-issue-comment@main
    with:
      issue-number: 123
      message: Your fine comment
```
