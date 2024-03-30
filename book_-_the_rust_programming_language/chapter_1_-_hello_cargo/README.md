# Hello, Cargo!

To create new project:
```
cargo new hello_cargo
```
This creates a folder named `hello_cargo` with the project structure including a `src` folder with a `main.rs` file (a hello world!) and a `Cargo.toml` file next to the `src` folder.

To compile this project with cargo:
```
cargo build
```
This creates the executable file `target/debug/hello_cargo`.

You can run this executable with:
```
./target/debug/hello_cargo
```

Code can also be compiled and executed at once by running:
```
cargo run
```

There's also a command to check the code compiles without producing an executable:
```
cargo check
```

When ready for release:
```
cargo build --release
```