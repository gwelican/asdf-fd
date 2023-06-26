<div align="center">

# asdf-fd [![Build](https://github.com/gwelican/asdf-fd/actions/workflows/build.yml/badge.svg)](https://github.com/gwelican/asdf-fd/actions/workflows/build.yml) [![Lint](https://github.com/gwelican/asdf-fd/actions/workflows/lint.yml/badge.svg)](https://github.com/gwelican/asdf-fd/actions/workflows/lint.yml)

[fd](https://github.com/sharkdp/fd) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add fd
# or
asdf plugin add fd https://github.com/gwelican/asdf-fd.git
```

fd:

```shell
# Show all installable versions
asdf list-all fd

# Install specific version
asdf install fd latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fd latest

# Now fd commands are available
fd --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gwelican/asdf-fd/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Varsanyi](https://github.com/gwelican/)
