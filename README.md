# HTTP-Rust

Rust のテストコンテナ

```bash
podman build -t http-rs .
podman run -p 8080:80 localhost/http-rs:latest
curl http://localhost:8080
```
