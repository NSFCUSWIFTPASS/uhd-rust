# UHD-Rust
Updated Rust bindings to the UHD (USRP Hardware Driver) library, which provides support for Ettus Research / National Instruments Universal Software Radio Peripheral device. Code modified from https://github.com/samcrow/uhd-rust.

## Documentation
Works with the UHD driver 4.3.0.0. Tested on a Raspberry Pi 4 (Raspbian 10 - buster) with Rust version 1.70.0 GNU C++ version 8.3.0.

Verify the connected USRP is working with ```uhd_usrp_probe```.

In the main folder: 
```
cargo build
cargo run --example receiver
```

## Dependencies
1.0.39 - Anyhow
0.2 - libc
0.4.0 - num-complex
1.0.24 - thiserror
0.1.2 - uhd-sys

## Dev-Dependencies
0.8.3 - env_logger
0.4.13 - log
1.0.1 - tap
