<div align="center">

# asdf-playwright [![Build](https://github.com/jbadeau/asdf-playwright/actions/workflows/build.yml/badge.svg)](https://github.com/jbadeau/asdf-playwright/actions/workflows/build.yml) [![Lint](https://github.com/jbadeau/asdf-playwright/actions/workflows/lint.yml/badge.svg)](https://github.com/jbadeau/asdf-playwright/actions/workflows/lint.yml)

[playwright](https://github.com/jbadeau/playwright) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add playwright
# or
asdf plugin add playwright https://github.com/jbadeau/asdf-playwright.git
```

playwright:

```shell
# Show all installable versions
asdf list-all playwright

# Install specific version
asdf install playwright latest

# Set a version globally (on your ~/.tool-versions file)
asdf global playwright latest

# Now playwright commands are available
playwright --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jbadeau/asdf-playwright/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Badeau, Jose](https://github.com/jbadeau/)
