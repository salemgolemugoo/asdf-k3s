# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test k3s https://github.com/dmpe/asdf-k3s.git "k3s -v"
```

Tests are automatically run in GitHub Actions on push and PR.
