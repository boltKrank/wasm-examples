# Rust WASM

## Dockerfile

```
FROM rust:1.67

WORKDIR /usr/src/myapp
COPY . .

RUN cargo install --path .

CMD ["myapp"]
```

### Hello world in Docker

https://github.com/mikesparr/tutorial-rust-docker
