<div align="center">

# asdf-ginkgo [![Build](https://github.com/smartcontractkit/asdf-ginkgo/actions/workflows/build.yml/badge.svg)](https://github.com/smartcontractkit/asdf-ginkgo/actions/workflows/build.yml) [![Lint](https://github.com/smartcontractkit/asdf-ginkgo/actions/workflows/lint.yml/badge.svg)](https://github.com/smartcontractkit/asdf-ginkgo/actions/workflows/lint.yml)


[ginkgo](https://github.com/onsi/ginkgo) plugin for the [asdf version manager](https://asdf-vm.com).

Based on https://github.com/jimmidyson/asdf-ginkgo

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `golang`

# Install

Plugin:

```shell
asdf plugin add ginkgo https://github.com/smartcontractkit/asdf-ginkgo.git
```

ginkgo:

```shell
# Show all installable versions
asdf list-all ginkgo

# Install specific version
asdf install ginkgo latest
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.
