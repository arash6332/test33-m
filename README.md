  RUST_BACKTRACE: 1
name: CI
on:
  pull_request:
     RUSTC_WRAPPER: sccache
      SCCACHE_CACHE_SIZE: 2G
