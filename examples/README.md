# Examples

This directory contains examples demonstrating how to use the extras-for-egui library.

## Running Examples

To run an example locally:

```bash
cargo run --example demo
```

## Available Examples

### demo

A simple demonstration application showing basic usage of the extras-for-egui library. This example shows how to integrate the library into your egui application.

Run with:
```bash
cargo run --example demo
```

## Building for Web

To build an example for the web using Trunk:

1. Install the required target: `rustup target add wasm32-unknown-unknown`
2. Install Trunk: `cargo install --locked trunk`
3. Run: `trunk serve examples/demo.rs`

Note: Web builds of examples currently use the same `index.html` as the main app template.
