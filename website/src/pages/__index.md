Gloo is a toolkit for building web applications and libraries with Rust and Wasm, composed of
modular crates. [Gloo crates](https://github.com/rustwasm/gloo/tree/master/crates)
include example code, both in their respective `example` folders, and commented in their code, as well
as [API documentation](https://docs.rs/gloo/).

## Gloo Crates

1. [`console`](https://crates.io/crates/gloo-console)
2. [`dialog`](https://crates.io/crates/gloo-dialog)
3. [`event`](https://crates.io/crates/gloo-event)
4. [`file`](https://crates.io/crates/gloo-file)
4. [`history`](https://crates.io/crates/gloo-history)
5. [`storage`](https://crates.io/crates/gloo-storage)
6. [`timer`](https://crates.io/crates/gloo-timer)
6. [`utils`](https://crates.io/crates/gloo-utils)
6. [`worker`](https://crates.io/crates/gloo-worker)

## Using Gloo

Gloo is a *modular* toolkit: Each of its crates can either be used via the
umbrella `gloo` crate, which re-exports all of them for a stream-lined, holistic
experience, or each crate can be used independently.

## Getting Started

Read our [Getting Started](docs/getting-started) guide to learn more. 
