***

- Install Rust via [rustup](https://rustup.rs), a toolchain management system.
- Can choose different compilation targets, list found [here](https://forge.rust-lang.org/release/platform-support.html).
- Three release channels: stable, nightly and beta.
- Inner development loop:
	- Make a change;
	- Compile the application;
	- Run tests;
	- Run the application;
- Can speed up linking in Rust by [using a non-default linker](obsidian://open?vault=zero2prod&file=code-snippets%2FChanging%20the%20default%20linker%20in%20Rust).
- Can trigger commands on every file change with `cargo-watch`.
- Continuous Integration (CI) pipeline. Can be done with [Github Actions](https://github.com/features/actions).
- Automatic formatting with `cargo fmt`.
- Static analysis with `cargo clippy`.
- Checking for security vulnerabilities with `cargo audit`.