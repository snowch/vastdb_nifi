# VastDB NiFi

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/vast-data/vastdb_nifi?style=flat-square)](https://github.com/vast-data/vastdb_nifi/releases)
[![Build Status](https://github.com/vast-data/vastdb_nifi/actions/workflows/main.yml/badge.svg)](https://github.com/vast-data/vastdb_nifi/actions/workflows/main.yml)
[![Supported Python versions](https://img.shields.io/badge/3.9&nbsp;%7C%203.10&nbsp;%7C%203.11-blue)](https://www.python.org/)
[![Supported Platforms](https://img.shields.io/badge/platform-macos%20%7C%20linux-lightgrey)](https://www.python.org/)
[![code style: ruff](https://img.shields.io/badge/code%20style-ruff-4B4483.svg)](https://github.com/astral-sh/ruff)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


-----

## Table of Contents

- [Installation](#installation)
- [Build](#build)
- [Develop](#develop)
- [License](#license)

## Installation

 - [NiFi Standard 2.0.0-M4](https://nifi.apache.org/download/) [or later] installed ([install docs](https://nifi.apache.org/docs/nifi-docs/html/getting-started.html#downloading-and-installing-nifi)).  The installation directory will be referred to as `$NIFI_HOME`.
 - Uncomment `nifi.python.command=python3` in `$NIFI_HOME/conf/nifi.properties`
 - Python3 must be 3.9+
 - Download the [nar file](https://github.com/vast-data/vastdb_nifi/releases/latest) for your platform and Python version
 - Add the nar file to `$NIFI_HOME/extensions`

## Build

```console
hatch build -t custom
```

## Develop

```console
git tag vX.Y.Z
git push origin --tags
```

## License

`vastdb-nifi` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
