# Websockets with ngrok-rs

Basic websockets example copied from
[axum](https://github.com/tokio-rs/axum/tree/main/examples/websockets), but
with an ngrok listener.

Run the server with `cargo run --bin example-websockets`.

Run the client with `cargo run --bin example-client -- wss://<hostname from server logs>/ws`.

