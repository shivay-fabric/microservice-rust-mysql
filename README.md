
Build
```
cargo build --target wasm32-wasi --release
```

## Run

```bash
wasmedge --env "DATABASE_URL=mysql://user:passwd@127.0.0.1:3306/mysql" order_demo_service.wasm
```
