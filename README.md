<div align="center">

# asdf-sqlc [![Build](https://github.com/ramonamorim/asdf-sqlc/actions/workflows/build.yml/badge.svg)](https://github.com/ramonamorim/asdf-sqlc/actions/workflows/build.yml) [![Lint](https://github.com/ramonamorim/asdf-sqlc/actions/workflows/lint.yml/badge.svg)](https://github.com/ramonamorim/asdf-sqlc/actions/workflows/lint.yml)

[sqlc](https://docs.sqlc.dev/en/latest/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sqlc
# or
asdf plugin add sqlc https://github.com/ramonamorim/asdf-sqlc.git
```

sqlc:

```shell
# Show all installable versions
asdf list-all sqlc

# Install specific version
asdf install sqlc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sqlc latest

# Now sqlc commands are available
sqlc version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ramonamorim/asdf-sqlc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ramon Amorim](https://github.com/ramonamorim/)
