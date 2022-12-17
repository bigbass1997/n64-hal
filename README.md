[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Crates.io](https://img.shields.io/crates/v/n64-hal?style=flat-square)](https://crates.io/crates/n64-hal)
[![Documentation](https://img.shields.io/docsrs/n64-hal?style=flat-square)](https://docs.rs/n64-hal)

### Description
`n64-hal` is a Rust HAL ([Hardware Abstraction Layer](https://rust-embedded.github.io/book/start/registers.html)) crate for the Nintendo 64 console.

### Usage
In your project's `Cargo.toml`:
```Toml
[dependencies]
n64-hal = "0.1"
```

Refer to the [docs](https://docs.rs/n64-hal) for examples.

This crate is only intended to be used in the N64 embedded environment. 

### Nightly Rust
Please note this crate requires a nightly rust toolchain in order to use nightly-only inline assembly features.