# Rust-Mumble Setup Script

A simple and automated script to install and configure [**Rust-Mumble made by AvarianKnight**](https://github.com/AvarianKnight/rust-mumble), a voice server for FiveM, including dependencies, firewall settings, and system optimizations.

## 1of1 Servers VPS Plan
We offer a VPS package to host the Mumble server only at $9.99 per month found [here.](https://billing.1of1servers.com/cart.php?a=view)
Full guide found [here.](https://docs.1of1servers.com/1of1-game-guides/fivem/external-zumble-rust-mumble-server)

## Features
- Installs required dependencies
- Sets up Rust and builds Rust-Mumble from source
- Configures system limits for better performance
- Generates self-signed certificates (if missing)
- Creates and enables a systemd service
- Configures firewall rules
- Starts Rust-Mumble automatically

Set up the special VPS server within minutes using our quick and painless set up guide found here, or a video guide found below

## Installation & Usage

Run the following command to **automatically install and set up Rust-Mumble**:

```bash
git clone https://github.com/1-of-1-Servers/setup-rust-mumble.git && cd setup-rust-mumble && chmod +x setup_rust_mumble.sh && sudo ./setup_rust_mumble.sh
