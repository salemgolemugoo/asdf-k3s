<div align="center">

# asdf-k3s [![Build](https://github.com/dmpe/asdf-k3s/actions/workflows/build.yml/badge.svg)](https://github.com/dmpe/asdf-k3s/actions/workflows/build.yml) [![Lint](https://github.com/dmpe/asdf-k3s/actions/workflows/lint.yml/badge.svg)](https://github.com/dmpe/asdf-k3s/actions/workflows/lint.yml)

[k3s](https://github.com/dmpe/k3s) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add k3s
# or
asdf plugin add k3s https://github.com/dmpe/asdf-k3s.git
```

k3s:

```shell
# Show all installable versions
asdf list-all k3s

# Install specific version
asdf install k3s latest

# Set a version globally (on your ~/.tool-versions file)
asdf global k3s latest

# Now k3s commands are available
k3s -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dmpe/asdf-k3s/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [John Malc](https://github.com/dmpe/)
