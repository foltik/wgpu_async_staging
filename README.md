# wgpu_async_staging

A modified version of [wgpu::util::StagingBelt](https://docs.rs/wgpu/0.6.0/wgpu/util/struct.StagingBelt.html) which is `Send + Sync` and has an async `recall()` method.

Requires nightly rust due to the use of async closures.
