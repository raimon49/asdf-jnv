<div align="center">

# asdf-jnv [![Build](https://github.com/raimon/asdf-jnv/actions/workflows/build.yml/badge.svg)](https://github.com/raimon/asdf-jnv/actions/workflows/build.yml) [![Lint](https://github.com/raimon/asdf-jnv/actions/workflows/lint.yml/badge.svg)](https://github.com/raimon/asdf-jnv/actions/workflows/lint.yml)

[jnv](https://github.com/raimon49/asdf-jnv) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add jnv
# or
asdf plugin add jnv https://github.com/raimon/asdf-jnv.git
```

jnv:

```shell
# Show all installable versions
asdf list-all jnv

# Install specific version
asdf install jnv latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jnv latest

# Now jnv commands are available
jnv --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/raimon/asdf-jnv/graphs/contributors)!

# License

See [LICENSE](LICENSE) 息 [raimon](https://github.com/raimon/)
