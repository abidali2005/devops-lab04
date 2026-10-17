# Build pipeline

See the Makefile.

## Usage

| Command      | What it does                                    |
|--------------|-------------------------------------------------|
| `make`       | Runs `check` and `test` (the default target)    |
| `make check` | Confirms `src/` exists and has `.txt` files     |
| `make build` | Converts each `src/*.txt` to uppercase in `out/` |
| `make test`  | Builds, then tests the output                   |
| `make count` | Reports the number of source files and words    |
| `make clean` | Removes the `out/` directory                    |
| `make ci`    | Runs `clean`, `check` and `test` in order       |
