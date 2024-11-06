<div align="center">

# asdf-plugin-template [![Build](https://github.com/powerman/asdf-plugin-template/actions/workflows/build.yml/badge.svg)](https://github.com/powerman/asdf-plugin-template/actions/workflows/build.yml) [![Lint](https://github.com/powerman/asdf-plugin-template/actions/workflows/lint.yml/badge.svg)](https://github.com/powerman/asdf-plugin-template/actions/workflows/lint.yml)

[plugin-template](https://github.com/asdf-vm/asdf-plugin-template) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add plugin-template
# or
asdf plugin add plugin-template https://github.com/powerman/asdf-plugin-template.git
```

plugin-template:

```shell
# Show all installable versions
asdf list-all plugin-template

# Install specific version
asdf install plugin-template latest

# Set a version globally (on your ~/.tool-versions file)
asdf global plugin-template latest

# Now plugin-template commands are available
plugin-template --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/powerman/asdf-plugin-template/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Alex Efros](https://github.com/powerman/)
