# qasync

![Maintenance](https://img.shields.io/maintenance/yes/2020)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/qasync)
![PyPI - License](https://img.shields.io/pypi/l/qasync)
![PyPI](https://img.shields.io/pypi/v/qasync)

## Introduction

`qasync` allows coroutines to be used in PyQt/PySide applications by providing an implementation of the `PEP 3156` event-loop. 

`qasync` is a fork of [asyncqt](https://github.com/gmarull/asyncqt), which is a fork of [quamash](https://github.com/harvimt/quamash). May it live longer than its predecessors. 

#### The future of `qasync`

`qasync` was created because `asyncqt` and `quamash` were no longer maintained. However, as of 28th February 2020, `asyncqt` appears to be active once more. 

**`qasync` will continue to be maintained, and will still be accepting pull requests.** Improvements to `asyncqt` will be pulled downstream, and improvements to `qasync` will be sent upstream.

## Requirements

`qasync` requires Python >= 3.6, and PyQt5 or PySide2.

## Installation

To install `qasync`, use `pip`:

```
pip install qasync
```

## License

You may use, modify and redistribute this software under the terms of the [BSD License](http://opensource.org/licenses/BSD-2-Clause). See [LICENSE](/LICENSE).
