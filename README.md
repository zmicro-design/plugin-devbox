# DEVBOX - Instant, easy, and predictable development environments

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-devbox.svg?label=Release)](https://github.com/zmicro-design/plugin-devbox/tags)
[![Build Status](https://github.com/zmicro-design/plugin-devbox/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-devbox/actions/workflows/test.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-devbox.svg)](https://github.com/zmicro-design/plugin-devbox/issues)

## Installation

To install the package, run:

```bash
zmicro plugin install devbox
```

### If you donot install [ZMicro](https://github.com/zcorky/zmicro):

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zmicro-design/plugin-devbox/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zmicro-design/plugin-devbox/master/install | bash
```

## Usage

```markdown
Virtual Machine Manager (v1.0.3)

DEVBOX is a tool for managing virtual machines, based on multipass and lima.

Usage:
  devbox start <name>         - Start a virtual machine
  devbox stop <name>          - Stop a virtual machine
  devbox restart <name>       - Restart a virtual machine
  devbox remove <name>        - Remove a virtual machine
  devbox exec <name>          - Connect shell to a virtual machine
  devbox inspect <name>       - Inspect a virtual machine
  devbox help                 - Show help

Example:
  devbox start test01
```

## License

ZMicro Design is released under the [MIT License](./LICENSE).
