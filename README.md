## Learning Rust

### Introduction

Rust is a systems programming language that runs blazingly fast, prevents segfaults, and guarantees thread safety. It aims to bring modern language design and an advanced type system to systems programming. Rust does not use a garbage collector, using advanced static analysis to provide deterministic drops instead. It accomplishes this via the concept of ownership.

### Installation

To install Rust, download and run rustup-init.exe from https://rustup.rs/.
This will install the Rust compiler and package manager, Cargo.

### Hello, World!

- Create a new project with `cargo new hello`
- Navigate to the project directory with `cd hello`
- Open src/main.rs in a text editor
- Add the following code:

```rust
fn main() {
    println!("Hello, world!");
}
```

- Run the project with `cargo run`
