# GitHub Stargazers Fetcher

This Rust project demonstrates how to make an asynchronous HTTP GET request to the GitHub API to fetch the stargazers of a specific repository. It uses the `reqwest` library for making HTTP requests and `serde` for deserializing the JSON response.

## Requirements

- Rust (latest stable version recommended)
- [Tokio](https://tokio.rs/) for asynchronous runtime
- [Reqwest](https://docs.rs/reqwest/latest/reqwest/) for HTTP requests
- [Serde](https://serde.rs/) for JSON deserialization

## Installation

1. Ensure you have Rust installed. If not, you can install it using [rustup](https://rustup.rs/).
2. Add the necessary dependencies to your `Cargo.toml` file:

```toml
[dependencies]
tokio = { version = "1", features = ["full"] }
reqwest = { version = "0.11", features = ["json"] }
serde = { version = "1.0", features = ["derive"] }
