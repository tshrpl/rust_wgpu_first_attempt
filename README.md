# command to run

```bash
RUST_BACKTRACE=1 RUSTFLAGS=--cfg=web_sys_unstable_apis cargo run-wasm shader_viewer
```

# important files to look at

[shader_viewer/src/main.rs](https://github.com/tshrpl/rust_wgpu_first_attempt/blob/main/shader_viewer/src/main.rs)
[shader_viewer/src/shader.wgsl](https://github.com/tshrpl/rust_wgpu_first_attempt/blob/main/shader_viewer/src/shader.wgsl)
