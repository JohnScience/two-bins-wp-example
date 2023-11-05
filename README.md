# Example of a project (workspace) with two binaries

Running binary 1:

```console
cargo run --bin bin1
```

Running binary 2:

```console
cargo run --bin bin2
```

## Warning

[Feature unification](https://doc.rust-lang.org/cargo/reference/features.html#feature-unification) can cause troubles if your binaries depend on libraries with conflicting [features](https://doc.rust-lang.org/cargo/reference/features.html).
