# py-mdbx
Python ctypes bindings for libmdbx

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg) [![PyPI version](https://badge.fury.io/py/mdbxpy.svg)](https://badge.fury.io/py/mdbxpy) 

This project provides Python ctypes bindings for the [libmdbx](https://github.com/erthink/libmdbx) library, a fast, compact, and feature-rich library designed for use in an embedded role within larger applications. It's a highly efficient, transactional key-value database that offers high performance, robustness, and a rich set of features, making it an ideal choice for many types of software projects, including but not limited to Ethereum node projects.

## About libmdbx

libmdbx is an extraordinarily fast, compact, powerful, embedded, transactional key-value database with robust ACID semantics in a tiny footprint and with several advantages:

- ACID-compliant with full Multi-Version Concurrency Control (MVCC)
- Support for fully serializable transactions and Read Committed isolation level by default
- Space-efficient with a disk/memory footprint less than that of other DBMSs
- Allows one writer at a time but supports many concurrent readers
- Outperforms many competitors including LMDB, LevelDB, RocksDB, and WiredTiger

The libmdbx library began as a fork of the Lightning Memory-Mapped Database (LMDB) but has since undergone heavy modifications to improve its performance and expand its features.

These Python ctypes bindings aim to bring the full power of the libmdbx library to Python developers, and they draw inspiration from the Go bindings for libmdbx, [mdbx-go](https://github.com/torquem-ch/mdbx-go).

## Installation

To install libmdbx Python ctypes bindings, use pip:

```bash
pip install mdbxpy
# or
pip install py-mdbx
```

## Usage (TODO)
Here's a quick example of how to use these bindings:

```python
import mdbx

# ... usage example ...
```

Documentation for more advanced usage and features is available in the docs/ directory of this repository. (TODO)

## Contributing (TODO)
Contributions to the development and improvement of Python ctypes bindings for libmdbx are very welcome! For more details on how to contribute, please see our Contributing Guide.

## Testing (TODO)
You can run the test suite with the following command:

```bash
pytest
```

## License
This project is licensed under the terms of the MIT License. See the LICENSE file for the full license text.

## Contact
For more information, please contact the project maintainers.

Your Name - @simonblack

Project Link: https://github.com/simonblack/mdbxpy

Acknowledgments
libmdbx - The power-packed database library for which this project provides Python bindings.
mdbx-go - The Go language bindings for libmdbx that inspired this Python project.
