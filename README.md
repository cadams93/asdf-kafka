<div align="center">

# asdf-kafka [![Build](https://github.com/cadams93/asdf-kafka/actions/workflows/build.yml/badge.svg)](https://github.com/cadams93/asdf-kafka/actions/workflows/build.yml) [![Lint](https://github.com/cadams93/asdf-kafka/actions/workflows/lint.yml/badge.svg)](https://github.com/cadams93/asdf-kafka/actions/workflows/lint.yml)


[kafka](https://github.com/cadams93/kafka) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kafka
# or
asdf plugin add kafka https://github.com/cadams93/asdf-kafka.git
```

kafka:

```shell
# Show all installable versions
asdf list-all kafka

# Install specific version
asdf install kafka latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kafka latest

# Now kafka commands are available
kafka --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/cadams93/asdf-kafka/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [callum.adams](https://github.com/cadams93/)
