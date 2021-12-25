<div align="center">

# asdf-yay [![Build](https://github.com/aaaaninja/asdf-yay/actions/workflows/build.yml/badge.svg)](https://github.com/aaaaninja/asdf-yay/actions/workflows/build.yml) [![Lint](https://github.com/aaaaninja/asdf-yay/actions/workflows/lint.yml/badge.svg)](https://github.com/aaaaninja/asdf-yay/actions/workflows/lint.yml)


[yay](https://github.com/aaaaninja/asdf-yay) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add yay
# or
asdf plugin add yay https://github.com/aaaaninja/asdf-yay.git
```

yay:

```shell
# Show all installable versions
asdf list-all yay

# Install specific version
asdf install yay latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yay latest

# Now yay commands are available
yay --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/aaaaninja/asdf-yay/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [aaaaninja](https://github.com/aaaaninja/)
