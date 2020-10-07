# Barebones Watch Face for Rust + Mynewt on PineTime Smart Watch

![Barebones Watch Face for Rust + Mynewt on PineTime Smart Watch](https://lupyuen.github.io/images/timesync-title.png)

Barebones, no frills Rust Watch Face for PineTime Smart Watch with LVGL and Mynewt...

1. Bluetooth LE Time Sync

1. Date and Time

1. Bluetooth Indicator

1. Power Indicator

Built with [`pinetime-watchface`](https://crates.io/crates/pinetime-watchface) framework for watch faces.

To select this watch face, set `WatchFaceType` in [`pinetime-rust-mynewt/rust/app/src/lib.rs`](https://github.com/lupyuen/pinetime-rust-mynewt/blob/master/rust/app/src/lib.rs)

```rust
/// Declare the Watch Face Type
type WatchFaceType = barebones_watchface::BarebonesWatchFace;
```

Refer to the article...

["Bluetooth Time Sync, Rust Watch Faces and LVGL on PineTime Mynewt
"](https://lupyuen.github.io/pinetime-rust-mynewt/articles/timesync)

TODO: Preview watch face in web browser with WebAssembly
