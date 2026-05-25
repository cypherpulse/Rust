# Rust Learning Project 🦀

Welcome to **LestGetRusty** — a hands-on learning repository for mastering the Rust programming language. This project contains practical examples and exercises to build foundational Rust skills.

## Overview

This repository is dedicated to learning Rust through small, focused projects. Each example builds on core Rust concepts including:

- **Variables and Data Types**
- **Functions and Control Flow**
- **Ownership and Borrowing**
- **Error Handling**
- **Testing and Debugging**
- **Cargo Package Management**

## Projects

### 1. Hello World (`hello_world/`)

The classic first Rust program demonstrating:
- Basic project setup
- Simple `println!` macro usage
- Compiling and running Rust binaries

**Run it:**
```bash
cd hello_world/hello_cargo
cargo run
```

### 2. Guessing Game (`guessing_game/`)

An interactive number guessing game showcasing:
- User input handling with `std::io`
- Random number generation with the `rand` crate
- Pattern matching and result handling
- Game loop implementation
- Input validation and error messages

**Run it:**
```bash
cd guessing_game
cargo run
```

**How to play:**
- The game generates a secret number between 1 and 100
- Enter your guesses one at a time
- The game tells you if your guess is too high or too low
- Continue until you guess correctly!

## Getting Started

### Prerequisites

- **Rust** (latest stable) — install from [rustup.rs](https://rustup.rs/)
- **Cargo** (comes with Rust)
- A text editor or IDE (VS Code, JetBrains IDE, etc.)

### Verify Installation

```bash
rustc --version
cargo --version
```

### Running Examples

Each project is a standalone Cargo package. Navigate to any project and run:

```bash
cargo build       # Compile the project
cargo run         # Build and run
cargo test        # Run tests
cargo check       # Check for compilation errors
```

## Learning Resources

### Official Rust Book
- **"The Rust Programming Language"** — available free at [doc.rust-lang.org/book/](https://doc.rust-lang.org/book/)
- Covers ownership, borrowing, error handling, and more

### Rustlings
- Interactive exercises — install with `cargo install rustlings`

### Rust by Example
- [doc.rust-lang.org/rust-by-example/](https://doc.rust-lang.org/rust-by-example/)

## Project Structure

```
gettingStarted/
├── hello_world/           # Classic first program
│   ├── main.rs
│   └── hello_cargo/       # Cargo project version
│       ├── Cargo.toml
│       └── src/main.rs
├── guessing_game/         # Interactive learning game
│   ├── Cargo.toml
│   └── src/main.rs
├── README.md             # This file
└── [utility scripts]
```

## Common Commands

| Command | Purpose |
|---------|---------|
| `cargo new <name>` | Create a new Rust project |
| `cargo build` | Compile in debug mode |
| `cargo build --release` | Compile optimized build |
| `cargo run` | Build and execute |
| `cargo test` | Run all tests |
| `cargo doc --open` | Generate and view documentation |
| `cargo check` | Quick syntax/type checking (no build) |
| `cargo clippy` | Linter for code improvements |
| `cargo fmt` | Automatic code formatting |

## Utility Scripts

- **`commit.sh`** — Generate realistic fake commits for practice
- **`fake-dated-commits.sh`** — Create backdated commits
- **`issuepr.sh`** — Generate mock GitHub issues and pull requests

## Tips for Learning

1. **Start small** — Understand each concept before moving on
2. **Experiment** — Modify the examples and observe what happens
3. **Read error messages** — Rust's compiler is very helpful
4. **Use `cargo check`** — It's faster than full builds during development
5. **Reference the docs** — Run `cargo doc --open` in any project

## Next Steps

After completing these examples, explore:
- [Collections](https://doc.rust-lang.org/book/ch08-00-common-collections.html) (Vectors, Strings, HashMaps)
- [Enums and Pattern Matching](https://doc.rust-lang.org/book/ch06-00-enums.html)
- [Modules and Crates](https://doc.rust-lang.org/book/ch07-00-managing-growing-projects-with-packages-modules-and-paths.html)
- [Trait Objects and Generics](https://doc.rust-lang.org/book/ch10-00-generics.html)
- [Lifetimes](https://doc.rust-lang.org/book/ch10-03-lifetime-syntax.html)

## License

This learning project is open source. Feel free to fork, modify, and learn!

---

**Happy learning! 🚀**
