<div align="center">

# asdf-atuin [![Build](https://github.com/nklmilojevic/asdf-atuin/actions/workflows/build.yml/badge.svg)](https://github.com/nklmilojevic/asdf-atuin/actions/workflows/build.yml) [![Lint](https://github.com/nklmilojevic/asdf-atuin/actions/workflows/lint.yml/badge.svg)](https://github.com/nklmilojevic/asdf-atuin/actions/workflows/lint.yml)

[atuin](asdf-atuin) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add atuin
# or
asdf plugin add atuin https://github.com/nklmilojevic/asdf-atuin.git
```

atuin:

```shell
# Show all installable versions
asdf list-all atuin

# Install specific version
asdf install atuin latest

# Set a version globally (on your ~/.tool-versions file)
asdf global atuin latest

# Now atuin commands are available
atuin --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nklmilojevic/asdf-atuin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikola Milojević](https://github.com/nklmilojevic/)
