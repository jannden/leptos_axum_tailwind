# Leptos + Axum + Tailwind Starter

This is a template demonstrating how to integrate [TailwindCSS](https://tailwindcss.com/) with the [Leptos](https://github.com/leptos-rs/leptos) web framework, [Axum](https://github.com/tokio-rs/axum) server, and the [cargo-leptos](https://github.com/akesson/cargo-leptos) tool.

This is a cleaned up version of the [official example](https://github.com/leptos-rs/leptos/tree/main/examples/tailwind_axum) for simpler installation.

## Pre-requisites

Make sure you have the following installed on your system:
- [Rust](https://www.rust-lang.org/tools/install)
- [Node.js](https://nodejs.org/en/download/)

## Install Leptos

```bash
cargo add leptos
```

Install client-side support (optional):

```bash
cargo install trunk
```

Install server-side support (necessary for this example):

```bash
cargo install cargo-leptos
```

Install WebAssembly target:

```bash
rustup target add wasm32-unknown-unknown
```

## Clone this project

Clone this repository with Git:
  
```bash
git clone https://github.com/jannden/leptos_axum_tailwind
```

Or optionally with Leptos:

```bash
cargo leptos new --git https://github.com/jannden/leptos_axum_tailwind
```

## Quick Start

Open the project directory, eg.:

```bash
cd leptos_axum_tailwind
```

Install the TailwindCSS dependencies:

```bash
npm install
npx update-browserslist-db@latest
```

Start the server:

```bash
cargo leptos watch
```

Open your browser and navigate to `http://localhost:3000`.

The page is hot-reloaded when you make changes to the source code.