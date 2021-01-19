## web-server-scratch
### Multy-threaded web server writed in Rust
This project was written with the goal of learning the basics of Rust.

### To run the project:
You'll need to have at least Rust 1.45, you can install it using [rustup](https://rustup.rs/).  
When you've cloned the repository just run ```cargo run```, then the server will listen on:

-  127.0.0.1:7878/ - Ok HTML page;
-  127.0.0.1:7878/sleep - Ok HTML page with delay of 5s;
-  127.0.0.1:7878/something-else - 404 HTML page;
  
The server will listen to 20 connections, then it'll shutdown gracefully (hopefully).
