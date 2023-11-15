<div align="center">

# asdf-pomerium-cli [![Build](https://github.com/haggishunk/asdf-pomerium-cli/actions/workflows/build.yml/badge.svg)](https://github.com/haggishunk/asdf-pomerium-cli/actions/workflows/build.yml) [![Lint](https://github.com/haggishunk/asdf-pomerium-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/haggishunk/asdf-pomerium-cli/actions/workflows/lint.yml)

[pomerium-cli](https://www.pomerium.com/docs/deploy/clients/pomerium-cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add pomerium-cli
# or
asdf plugin add pomerium-cli https://github.com/haggishunk/asdf-pomerium-cli.git
```

pomerium-cli:

```shell
# Show all installable versions
asdf list-all pomerium-cli

# Install specific version
asdf install pomerium-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pomerium-cli latest

# Now pomerium-cli commands are available
pomerium-cli version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/haggishunk/asdf-pomerium-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Travis Mattera](https://github.com/haggishunk/)
