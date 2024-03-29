# Actix JWT

This repository provides of:

- Actix REST API
- Actix CORS config
- Error handling
- JWT authentication
- Interaction with the MySql database
- Password encryption
- Payload validation

## Required

- Rust
- Docker and docker-compose or Postgresql server

## Usage

- edit .env
- `cargo run --release` or `debug with vscode`

## Docker build

- `docker buildx build . -t aimdevgroup/sample-actix-rust-api  --platform linux/amd64 --push`
