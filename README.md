# Rust

This is my first attempts to learn [Rust](https://www.rust-lang.org/) using [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/).

## Instructions

You do not need to install Rust.  This is set up using the [Official Docker Rust image](https://hub.docker.com/_/rust).

1. Start the container with `docker-compose up`. This will start the docker container named `rust-container`.
2. The container runs in stdin mode.  Access the terminal with `docker exec -it rusty-container /bin/bash`.
3. Compile one of the practice Rust examples, e.g. from the `src` directory use `rustc hello/hello-world.rs --out-dir hello`.
4. Run the compiled script with `./hello/hello-world`.