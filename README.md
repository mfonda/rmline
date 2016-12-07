# rmline

`rmline` is a quick n' dirty tool that rewrites a given file, removing the given line
or range of lines, and outputs the removed lines to stdout.

`rmline` may not handle large files very well as the entire file is loaded into memory
and the entire file is rewritten. No attempts at optimatization have been made; just
a quick tool good enough for my use cases. Contributions are welcome.

## Installation

Place `rmline` into your path. Requires PHP.

## Usage

```
rmline <filename> <line number> [ending line number]
```
