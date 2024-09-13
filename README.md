# VastDB NiFi

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/snowch/vastdb_nifi?style=flat-square)](https://github.com/snowch/vastdb_nifi/releases)
[![Build Status](https://github.com/snowch/vastdb_nifi/actions/workflows/main.yml/badge.svg)](https://github.com/snowch/vastdb_nifi/actions/workflows/main.yml)
[![Supported Python versions](https://img.shields.io/badge/python-3.7&nbsp;%7C%203.8&nbsp;%7C%203.9&nbsp;%7C%203.10&nbsp;%7C%203.11-blue)](https://www.python.org/)
[![Supported Platforms](https://img.shields.io/badge/platform-macos%20%7C%20linux-lightgrey)](https://www.python.org/)

-----

## Table of Contents

- [Installation](#installation)
- [Build](#build)
- [License](#license)

## Installation

 - [NiFi Standard 2.0.0-M4](https://nifi.apache.org/download/) [or later] installed (the installation directory will be referred to as `$NIFI_HOME`)
 - Uncomment `nifi.python.command=python3` in `$NIFI_HOME/conf/nifi.properties`
 - Python3 must be 3.9+
 - Download the [nar file](https://github.com/snowch/vastdb_nifi/releases/latest) for your platform and Python version
 - Add the nar file to `$NIFI_HOME/extensions`

## Build

```console
hatch build -t custom
```

## License

`vastdb-nifi` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
