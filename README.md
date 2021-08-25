# OSDU SDK for Python

[![Build](https://github.com/equinor/osdu-sdk-python/actions/workflows/build.yml/badge.svg)](https://github.com/equinor/osdu-cli/actions/workflows/build.yml)
[![License](https://img.shields.io/pypi/l/osdu-sdk-python.svg)](https://github.com/equinor/osdu-sdk-python/blob/master/LICENSE)
[![PyPi Version](https://img.shields.io/pypi/v/osdu-sdk-python.svg?color=informational)](https://pypi.org/project/osdu/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/osdu-sdk-python.svg?color=informational)](https://pypi.org/project/osdu/)
![Unknown coverage](https://img.shields.io/badge/coverage-%3F%3F%3F-important)

This is the OSDU SDK for Python (work in progress).

:warning: Note that this is a work in progress and is not complete / might contain bugs.

## Installation

Usage requires that you have a valid python 3.8+ installation on your machine. You might also consider creating a seperate python [virtual environment](https://docs.python.org/3/library/venv.html) for working with OSDU.

### Alternative 1 - Deploy from PyPi

For general usage deploying from [PyPi](https://pypi.org/project/osdu/) is the easiest and recommended method.

```bash
pip install osdu
```

### Alternative 2 - Developer setup

For those wanting to modify the code. 
See the
[corresponding wiki](https://github.com/equinor/osdu/wiki) for
more information.

## Usage

TODO

## Contributing

We welcome any kind of contribution, whether it be reporting issues or sending pull requests.

When contributing to this repository abide by the
[Equinor Open Source Code of Conduct](https://github.com/equinor/opensource/blob/master/CODE_OF_CONDUCT.md).


### CLI specific issues and requests

If your issue is relevant to the OSDU CLI, please use this repositories [issue tracker](https://github.com/equinor/osdu-sdk-python/issues).

Be sure to search for similar previously reported issues prior to creating a new one.
In addition, here are some good practices to follow when reporting issues:

- Add a `+1` reaction to existing issues that are affecting you
- Include verbose output (`--debug` flag) when reporting unexpected error messages
- Include the version of OSDU SDK for Python installed, `pip show osdu` will report this
- Include the version of OSDU you are using

### Code changes

See the
[wiki page on contributing](https://github.com/equinor/osdu-sdk-python/wiki) for
more information on submitting code changes.
