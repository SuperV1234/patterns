# MPark.Patterns

> Pattern Matching in __C++14__.

[![stability][badge.stability]][stability]
[![license][badge.license]][license]
[![wandbox][badge.wandbox]][wandbox]

[badge.stability]: https://img.shields.io/badge/stability-experimental-orange.svg
[badge.license]: http://img.shields.io/badge/license-boost-blue.svg
[badge.wandbox]: https://img.shields.io/badge/try%20it-on%20wandbox-green.svg

[stability]: http://github.com/badges/stability-badges
[license]: https://github.com/mpark/patterns/blob/master/LICENSE_1_0.txt
[wandbox]: https://wandbox.org/permlink/AHuPKUpF6mQudvr8

## Test

This directory contains the tests for __MPark.Patterns__.

### Building and Running Tests

Execute the following commands from the top-level directory:

```bash
mkdir build
cd build
cmake -DMPARK_PATTERNS_INCLUDE_TESTS=ON ..
cmake --build .
ctest -V
```
