# Bloa Tools

A collection of tools for the Bloa programming language, including a formatter and linter.

## Features

- **Formatter**: Automatically formats Bloa code according to standard conventions.
- **Linter**: Checks Bloa code for style and potential errors.

## Installation

Clone the Bloa interpreter repository and build it:

```bash
git clone https://github.com/bloa-lang/bloa-src.git
cd bloa-src
mkdir -p build && cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
cmake --build .
```

## Usage

### Formatter

```bash
/path/to/bloa /path/to/bloa-tools/src/formatter.bloa <input_file> <output_file>
```

### Linter

```bash
/path/to/bloa /path/to/bloa-tools/src/linter.bloa <input_file>
```

## Notes

The tools are implemented in Bloa itself. Some advanced features may have limitations due to the current Bloa standard library. The formatter handles basic indentation and semicolon addition. The linter checks for indentation consistency and missing semicolons.

## Development

Run tests (currently manual):

```bash
/path/to/bloa /path/to/bloa-tools/run_tests.bloa
```