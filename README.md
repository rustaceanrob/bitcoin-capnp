# Bitcoin Core IPC Schema Files

The `libmultiprocess` project in Bitcoin Core allows for external processes on a machine to communicate with a `bitcoind` process over Unix sockets. These schemas define the interface for communicating with `bitcoind`. Tools like [Rust `capnp`](https://docs.rs/capnp/latest/capnp/) may be used to auto-generate client code based on these schemas.
