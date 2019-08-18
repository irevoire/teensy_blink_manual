# This repository is an example of usage for the [teensy crate](https://github.com/irevoire/teensy)

The major things to see here are:
- [The usage of  the `manual_init` feature in the `cargo.toml`.](https://github.com/irevoire/teensy_blink_manual/blob/master/Cargo.toml#L9-L12)
- [The definition of the init function in the `main.rs`.](https://github.com/irevoire/teensy_blink_manual/blob/master/src/main.rs#L9-L17)

To fast test this example on your teensy run:
```
sh configure.sh
make flash
```
