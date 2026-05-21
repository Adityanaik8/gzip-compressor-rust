# Gzip Compressor in Rust

A simple command-line gzip compressor built using Rust and the flate2 crate.

## Features

- Compress files into `.gz`
- Buffered file reading
- Measures compression time
- Shows source and compressed file size

## Usage

```bash
cargo run input.txt output.gz
