<div align="center">

# asdf-mint [![Build](https://github.com/MontakOleg/asdf-mint/actions/workflows/build.yml/badge.svg)](https://github.com/MontakOleg/asdf-mint/actions/workflows/build.yml) [![Lint](https://github.com/MontakOleg/asdf-mint/actions/workflows/lint.yml/badge.svg)](https://github.com/MontakOleg/asdf-mint/actions/workflows/lint.yml)

[mint](https://github.com/yonaskolb/Mint) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add mint
# or
asdf plugin add mint https://github.com/MontakOleg/asdf-mint.git
```

mint:

```shell
# Show all installable versions
asdf list-all mint

# Install specific version
asdf install mint latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mint latest

# Now mint commands are available
mint version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MontakOleg/asdf-mint/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Oleg Montak](https://github.com/MontakOleg/)
