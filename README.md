<div align="center">

# asdf-hostess [![Build](https://github.com/herberton/asdf-hostess/actions/workflows/build.yml/badge.svg)](https://github.com/herberton/asdf-hostess/actions/workflows/build.yml) [![Lint](https://github.com/herberton/asdf-hostess/actions/workflows/lint.yml/badge.svg)](https://github.com/herberton/asdf-hostess/actions/workflows/lint.yml)

[hostess](https://github.com/cbednarski/hostess) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add hostess
# or
asdf plugin add hostess https://github.com/herberton/asdf-hostess.git
```

hostess:

```shell
# Show all installable versions
asdf list-all hostess

# Install specific version
asdf install hostess latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hostess latest

# Now hostess commands are available
hostess -h
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/herberton/asdf-hostess/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Herberton Candido Souza](https://github.com/herberton/)
