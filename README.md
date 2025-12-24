# extras-for-egui

[![dependency status](https://deps.rs/repo/github/itsNiccoloSabatini/extras-for-egui/status.svg)](https://deps.rs/repo/github/itsNiccoloSabatini/extras-for-egui)
[![Build Status](https://github.com/itsNiccoloSabatini/extras-for-egui/workflows/CI/badge.svg)](https://github.com/itsNiccoloSabatini/extras-for-egui/actions?workflow=CI)

A collection of extra widgets and utilities for [egui](https://github.com/emilk/egui).

This library provides additional widgets and helpers that extend the functionality of egui, making it easier to build rich graphical user interfaces.

## Installation

Add this to your `Cargo.toml`:

```toml
[dependencies]
extras-for-egui = "0.1.0-alpha.1"
egui = "0.33.0"
```

## Usage

```rust
use extras_for_egui::widgets;

// Use the widgets in your egui application
fn my_ui(ui: &mut egui::Ui) {
    // Widget usage examples will be added here as the library grows
}
```

## Examples

See the [`examples/`](examples/) directory for complete usage examples.

To run the demo example:

```bash
cargo run --example demo
```

## Features

This library is in early development. More widgets and features will be added over time.

## Development

### Building

```bash
cargo build
```

### Testing

```bash
cargo test
```

### Running Examples

```bash
cargo run --example demo
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

Licensed under either of

* Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
* MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Acknowledgments

Built on top of the excellent [egui](https://github.com/emilk/egui) library by Emil Ernerfeldt.

