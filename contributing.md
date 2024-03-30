# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test git-worktree-wrapper https://github.com/kedwards/asdf-git-worktree-wrapper.git "git-worktree-wrapper --help"
```

Tests are automatically run in GitHub Actions on push and PR.
