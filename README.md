# intx

[![readme style: standard][readme style standard badge]][standard readme]

> Extended precision integer C++ library

Provides following types:

- `uint128`,
- `uint256`,
- `uint512`.

## Usage

To build, test or benchmark.

```bash
git clone https://github.com/chfast/intx
cd intx

cmake -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build --parallel

build/test/intx-unittests
build/test/intx-bench
```

## Maintainer

Paweł Bylica [@chfast]

## License

Licensed under the [Apache License, Version 2.0].


[@chfast]: https://github.com/chfast
[Apache License, Version 2.0]: LICENSE
[standard readme]: https://github.com/RichardLitt/standard-readme

[readme style standard badge]: https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square

