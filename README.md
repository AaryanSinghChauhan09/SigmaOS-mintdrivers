# SigmaOS mintdrivers

This crate is currently a `no_std` identity scaffold. Its only public type
constructs a `Component` with the fixed name `SigmaOS Component`. It does not
discover devices, install drivers, or change hardware configuration.

The inline unit test checks only the fixed scaffold name. It does not exercise
driver discovery or installation.

## Build

```sh
cargo check --lib
```

## License

Apache-2.0. See [`Cargo.toml`](Cargo.toml).
