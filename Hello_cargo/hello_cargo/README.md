We can use cargo run to do both compilation and run the code all in one command. This is an alternative instead of running cargo build and then running ./target/debug/hello_cargo.

Cargo also provides a command called cargo check which basically checks the code to make sure it compiles but doesn't produce an executable. 

Building for Release:

We use cargo build --release when the project is finally ready for release to compile with optimiations. This command creates an executable target/release instead of target/debug.

Cargo as a Convention:

Once a program becomes more complex and has muiltiple files, cargo comes in but when the project is simple using rustc is more easier. 