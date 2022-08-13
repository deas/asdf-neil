<div align="center">

# asdf-neil [![Build](https://github.com/deas/asdf-neil/actions/workflows/build.yml/badge.svg)](https://github.com/deas/asdf-neil/actions/workflows/build.yml) [![Lint](https://github.com/deas/asdf-neil/actions/workflows/lint.yml/badge.svg)](https://github.com/deas/asdf-neil/actions/workflows/lint.yml)


[neil](https://github.com/babashka/neil) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add neil
# or
asdf plugin add neil https://github.com/deas/asdf-neil.git
```

neil:

```shell
# Show all installable versions
asdf list-all neil

# Install specific version
asdf install neil latest

# Set a version globally (on your ~/.tool-versions file)
asdf global neil latest

# Now neil commands are available
neil --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/deas/asdf-neil/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andreas Steffan](https://github.com/deas/)
