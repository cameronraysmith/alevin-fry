# alevin-fry ![Rust](https://github.com/COMBINE-lab/alevin-fry/workflows/Rust/badge.svg)

Absolutely RADic(a)l methods for analyzing single-cell sequencing data (written in Rust)!

## Building

Alevin-fry is built and tested with the latest (major & minor version) stable Rust (currently 1.45).
Building should be as easy as:

```{bash}
$ cargo build --release
```

subsequent commands below will assume that the executable is in your path.  Temporarily, this can 
be done (in bash-like shells) using:

```{bash}
$ export PATH=`pwd`/target/release/:$PATH
```

## Documentation 

Alevin-fry is under active development.  However, you can find the documentation on [read the docs](https://alevin-fry.readthedocs.io/en/latest/).  We try to keep the documentation up to date with the latest developments in the software.
