<div align="center">

# asdf-kluctl [![Build](https://github.com/svenluijten/asdf-kluctl/actions/workflows/build.yml/badge.svg)](https://github.com/svenluijten/asdf-kluctl/actions/workflows/build.yml) [![Lint](https://github.com/svenluijten/asdf-kluctl/actions/workflows/lint.yml/badge.svg)](https://github.com/svenluijten/asdf-kluctl/actions/workflows/lint.yml)


[kluctl](https://kluctl.io/docs/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kluctl
# or
asdf plugin add kluctl https://github.com/svenluijten/asdf-kluctl.git
```

kluctl:

```shell
# Show all installable versions
asdf list-all kluctl

# Install specific version
asdf install kluctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kluctl latest

# Now kluctl commands are available
kluctl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/svenluijten/asdf-kluctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sven Luijten](https://github.com/svenluijten/)
