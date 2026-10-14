# bench-tools

A small harness for timing functions with warmup and repeat runs.

## Why

I kept rewriting the same thirty lines in every project, so I pulled them out.

## Install

```bash
pip install bench-tools
```

## Usage

```python
from bench_tools import benchTools

result = benchTools("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
