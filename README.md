<div align="center">

# asdf-XcodeSelectiveTesting [![Build](https://github.com/Ernest0-Production/asdf-XcodeSelectiveTesting/actions/workflows/build.yml/badge.svg)](https://github.com/Ernest0-Production/asdf-XcodeSelectiveTesting/actions/workflows/build.yml) [![Lint](https://github.com/Ernest0-Production/asdf-XcodeSelectiveTesting/actions/workflows/lint.yml/badge.svg)](https://github.com/Ernest0-Production/asdf-XcodeSelectiveTesting/actions/workflows/lint.yml)

[XcodeSelectiveTesting](https://github.com/mikeger/XcodeSelectiveTesting) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-XcodeSelectiveTesting  ](#asdf-xcodeselectivetesting--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add XcodeSelectiveTesting
# or
asdf plugin add XcodeSelectiveTesting https://github.com/Ernest0-Production/asdf-XcodeSelectiveTesting.git
```

XcodeSelectiveTesting:

```shell
# Show all installable versions
asdf list-all XcodeSelectiveTesting

# Install specific version
asdf install XcodeSelectiveTesting latest

# Set a version globally (on your ~/.tool-versions file)
asdf global XcodeSelectiveTesting latest

# Now XcodeSelectiveTesting commands are available
xcode-selective-test --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Ernest0-Production/asdf-XcodeSelectiveTesting/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ernest0N](https://github.com/Ernest0-Production/)
