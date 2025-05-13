# pixelab-core

[![no_std](https://img.shields.io/badge/no__std-compatible-blue)](https://docs.rust-embedded.org/book/intro/no-std.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![crates.io](https://img.shields.io/crates/v/pixelab-core)](https://crates.io/crates/pixelab-core)

**Zero-OS-Dependency Core** - Building blocks for bare-metal to GUI applications  
*(Part of the [Pixelab ecosystem](https://github.com/ER-hamed/pixelab-rs))*

---

## Architecture
- 🧠 **Pure `core`**: No `std` dependency, works in `no_std` environments
- 🧲 **Hardware Agnostic**: Abstracts over display/input hardware
- 🔌 **OS Interface Ready**: Trait-based design for platform integration
- 🧩 **Atomic Primitives**: `Color`, `Point`, `Area`, `BitMap`

---

## Usage
Add to `Cargo.toml`:
```toml
[dependencies]
pixelab-core = { version = "0.1", default-features = false }
