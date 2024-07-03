<div align="center">

# asdf-vac [![Build](https://github.com/bodgit/asdf-vac/actions/workflows/build.yml/badge.svg)](https://github.com/bodgit/asdf-vac/actions/workflows/build.yml) [![Lint](https://github.com/bodgit/asdf-vac/actions/workflows/lint.yml/badge.svg)](https://github.com/bodgit/asdf-vac/actions/workflows/lint.yml)

[vac](https://github.com/mvisonneau/vac) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add vac
# or
asdf plugin add vac https://github.com/bodgit/asdf-vac.git
```

vac:

```shell
# Show all installable versions
asdf list-all vac

# Install specific version
asdf install vac latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vac latest

# Now vac commands are available
vac --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bodgit/asdf-vac/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Matt Dainty](https://github.com/bodgit/)
