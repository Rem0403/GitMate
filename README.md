## Getting Started

### 1. Install Rust

**Windows:**
- Download and run `rustup-init.exe` from https://rustup.rs
- Follow the prompts (default options are fine)
- If prompted, install the Microsoft C++ Build Tools
- Restart your terminal afterward

**macOS for Summah**
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source "$HOME/.cargo/env"
```

### 2. Verify the install
```bash
rustc --version
cargo --version
```
Both should print a version number.

### 3. Clone the repo and run it
```bash
git clone https://github.com/<your-username>/GitMate.git
cd GitMate
cargo run
```

### VS Code setup
- Install the rust-analyzer
- Install dependi
- Install even better toml
- Open the project folder (the one containing `Cargo.toml`) via File → Open Folder

If you're confused go to this youtube link right here: https://youtu.be/ZhedgZtd8gw
