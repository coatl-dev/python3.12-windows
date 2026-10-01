# Python 3.12 Installers for Windows

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/coatl-dev/python3.12/coatl.svg)](https://results.pre-commit.ci/latest/github/coatl-dev/python3.12-windows/coatl)
![GitHub Release](https://img.shields.io/github/v/release/coatl-dev/python3.12-windows)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/coatl-dev/python3.12-windows/total)

This repository provides binary installers for Python 3.12 on Windows.

## Motivation

Python 3.12 has reached the end of its regular bugfix support (see: [PEP 693]), obtaining official installers can become challenging. This repository aims to bridge that gap by hosting the necessary installers for Windows users.

## Available Installers

| Architecture | Installer                 | Notes                                |
|--------------|---------------------------|--------------------------------------|
| x86          | `python-3.12.*.exe`       | For 32-bit systems                   |
| x64          | `python-3.12.*-amd64.exe` | For 64-bit systems (Recommended)     |

## Installation

Download the appropriate installer for your system from the repository's [releases] section and follow the standard installation process for Python on Windows.

Alternatively you can install this via [Scoop], the Windows command-line installer. First, add our bucket:

```powershell
scoop bucket add coatl-dev https://github.com/coatl-dev/scoop-coatl-dev
```

And then, run:

```powershell
scoop install coatl-dev/python312
```

## License

This repository is provided for convenience and follows the licensing terms of Python Software Foundation.

[PEP 693]: https://peps.python.org/pep-0693/
[releases]: https://github.com/coatl-dev/python3.12-windows/releases
[Scoop]: https://scoop.sh/
