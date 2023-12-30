# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test my-rtx https://github.com/chrisboyce/my-rtx.git "my-rtx --help"
```

Tests are automatically run in GitHub Actions on push and PR.
