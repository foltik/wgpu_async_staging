# wgpu_async_staging

A modified version of [wgpu::util::StagingBelt](https://docs.rs/wgpu/latest/wgpu/util/struct.StagingBelt.html) which is `Send + Sync` and has an async `recall()` method.

Compatible with stable Rust and wgpu 25+.
