<div align="center">

# asdf-my-rtx [![Build](https://github.com/chrisboyce/asdf-my-rtx/actions/workflows/build.yml/badge.svg)](https://github.com/chrisboyce/asdf-my-rtx/actions/workflows/build.yml) [![Lint](https://github.com/chrisboyce/asdf-my-rtx/actions/workflows/lint.yml/badge.svg)](https://github.com/chrisboyce/asdf-my-rtx/actions/workflows/lint.yml)

[my-rtx](https://github.com/chrisboyce/my-rtx) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add my-rtx
# or
asdf plugin add my-rtx https://github.com/chrisboyce/asdf-my-rtx.git
```

my-rtx:

```shell
# Show all installable versions
asdf list-all my-rtx

# Install specific version
asdf install my-rtx latest

# Set a version globally (on your ~/.tool-versions file)
asdf global my-rtx latest

# Now my-rtx commands are available
my-rtx --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chrisboyce/asdf-my-rtx/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Chris Boyce](https://github.com/chrisboyce/)
