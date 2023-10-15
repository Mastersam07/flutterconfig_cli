## FlutterConfig CLI

[![FlutterConfig CLI](https://github.com/Mastersam07/flutterconfig/actions/workflows/ci.yaml/badge.svg?branch=dev)](https://github.com/Mastersam07/flutterconfig/actions/workflows/ci.yaml)
[![codecov](https://codecov.io/gh/Mastersam07/flutterconfig/graph/badge.svg?token=uTZC3hYm7Y&co)](https://codecov.io/gh/Mastersam07/flutterconfig)
[![License: Apache][license_badge]][license_link]

FlutterConfig CLI to help with configurations in your applications.

---

## Getting Started 🚀

If the CLI application is available on [pub](https://pub.dev), activate globally via:

```sh
dart pub global activate flutterconfig_cli
```

Or locally via:

```sh
dart pub global activate --source=path <path to this package>
```

## Usage

```sh
# Sample command
$ flutterconfig sample

# Sample command option
$ flutterconfig sample --cyan

# Show CLI version
$ flutterconfig --version

# Show usage help
$ flutterconfig --help
```

## Running Tests with coverage 🧪

To run all unit tests use the following command:

```sh
$ dart pub global activate coverage 1.2.0
$ dart test --coverage=coverage
$ dart pub global run coverage:format_coverage --lcov --in=coverage --out=coverage/lcov.info
```

To view the generated coverage report you can use [lcov](https://github.com/linux-test-project/lcov)
.

```sh
# Generate Coverage Report
$ genhtml coverage/lcov.info -o coverage/

# Open Coverage Report
$ open coverage/index.html
```

---

[coverage_badge]: coverage_badge.svg
[license_badge]: https://img.shields.io/badge/license-Apache--2.0-success.svg
[license_link]: ./LICENSE
