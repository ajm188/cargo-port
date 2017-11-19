# cargo-port
MacPorts for [cargo][cargo].

## Usage

This cargo port uses [rustup][rustup] to handle the bootstrapping required for cargo.
It then cleans up rustup-related files, leaving just the final cargo binary.

## Does it work?

Your mileage may vary.
Testing went as follows:

```bash
$ sudo port install cargo
$ cd to-various-rust-projects
$ cargo build  # => exiting cleanly
```

[cargo]: https://github.com/rust-lang/cargo
[rustup]: https://github.com/rust-lang-nursery/rustup.rs
