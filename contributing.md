# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test kluctl https://github.com/svenluijten/asdf-kluctl.git "kluctl version"
```

Tests are automatically run in GitHub Actions on push and PR.
