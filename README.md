# hello-yew
"Hello World" for Yew.


To deploy:

0. Make sure Rust is up-to-date `rustup update`.

1. Make sure WASM build target is installed: `rustup target add wasm32-unknown-unknown`

2. Install Trunk, Yew's recommended tool for managing deployment and packaging: `cargo install trunk`

3. In a CLI, run: `trunk serve --open` (within the project folder), which should open a browser window showing the built Yew app.
