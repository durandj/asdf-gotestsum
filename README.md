<div align="center">

# asdf-gotestsum [![Build](https://github.com/durandj/asdf-gotestsum/actions/workflows/build.yml/badge.svg)](https://github.com/durandj/asdf-gotestsum/actions/workflows/build.yml) [![Lint](https://github.com/durandj/asdf-gotestsum/actions/workflows/lint.yml/badge.svg)](https://github.com/durandj/asdf-gotestsum/actions/workflows/lint.yml)


[gotestsum](https://github.com/gotestyourself/gotestsum) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gotestsum
# or
asdf plugin add gotestsum https://github.com/durandj/asdf-gotestsum.git
```

gotestsum:

```shell
# Show all installable versions
asdf list-all gotestsum

# Install specific version
asdf install gotestsum latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gotestsum latest

# Now gotestsum commands are available
--version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/durandj/asdf-gotestsum/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [James Durand](https://github.com/durandj/)
