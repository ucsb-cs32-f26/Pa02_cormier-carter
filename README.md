# P02 Part 1: Malloc with an Implicit Free List

The full instructions are in the P02 Part 1 writeup. Each function in
`src/mm-implicit.c` has a comment describing exactly what it must do.

## Build and run

```bash
make
./bin/mdriver-implicit
```

On an Apple Silicon Mac, build for x86 instead (runs under Rosetta):

```bash
make clean
make CC="clang -arch x86_64"
```

## Useful driver flags

- `./bin/mdriver-implicit -c traces/short2.rep` runs one trace once and only checks correctness.
- `./bin/mdriver-implicit -D` calls your `mm_checkheap` before every operation.

## What to submit

Only `src/mm-implicit.c`.
