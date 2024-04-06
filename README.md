# Ore CLI

A command line interface for the Ore program.

## Usage
`ore --rpc "$public_rpc_url" --post-prc "$rpc_url" --keypair "${keypair}" --priority-fee 300000 mine --threads 20`

## Building

To build the Ore CLI, you will need to have the Rust programming language installed. You can install Rust by following the instructions on the [Rust website](https://www.rust-lang.org/tools/install).

Once you have Rust installed, you can build the Ore CLI by running the following command:

```sh
cargo build --release
```
