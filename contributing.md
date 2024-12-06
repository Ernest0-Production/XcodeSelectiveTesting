# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test XcodeSelectiveTesting https://github.com/Ernest0-Production/asdf-XcodeSelectiveTesting.git "xcode-selective-test --help"
```

Tests are automatically run in GitHub Actions on push and PR.
