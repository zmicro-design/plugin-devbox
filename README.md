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
Instant, easy, and predictable development environments (v1.0.2)

DEVBOX is a tool for managing virtual machines, based on multipass and lima.

Usage:
  devbox init                 - Initialize a directory as a devbox project
  devbox add <language>       - Add a language, such as nodejs,go,rust,python,java,deno
  devbox shell <name>         - Start a new shell or run a command with access to your packages
  devbox create <name>        - Create a new devbox
  devbox remove <name>        - Remove a devbox
  devbox ls                   - List all devboxes
  devbox inspect <name>       - Inspect a dexbox
  devbox help                 - Show help

Example:
  devbox init
  devbox add nodejs
  devbox shell
```

## License

ZMicro Design is released under the [MIT License](./LICENSE).
