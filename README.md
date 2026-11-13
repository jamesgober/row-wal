<h1 align="center">
    <strong>row-wal</strong>
    <br>
    <sup><sub>ROW-FORMAT WRITE-AHEAD LOG</sub></sup>
</h1>

<p align="center">
    <a href="https://crates.io/crates/row-wal"><img alt="crates.io" src="https://img.shields.io/crates/v/row-wal.svg"></a>
    <a href="https://docs.rs/row-wal"><img alt="docs.rs" src="https://docs.rs/row-wal/badge.svg"></a>
    <a href="https://github.com/jamesgober/row-wal/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/jamesgober/row-wal/actions/workflows/ci.yml/badge.svg"></a>
    <a href="#license"><img alt="license" src="https://img.shields.io/badge/license-Apache--2.0%20OR%20MIT-blue.svg"></a>
</p>

<p align="center">Conventional row-format WAL primitive. Group commit, fsync coordination, crash recovery, replay. Backend-agnostic durability.</p>

---

## Status

**Active development.** Scaffolded and on the path to 1.0. See [dev/ROADMAP.md](dev/ROADMAP.md) for milestone tracking.

The public API is not yet stable. Pin specific versions; expect changes pre-1.0.

---

## What it does

Row-format write-ahead log primitive for Rust databases. Group commit, fsync coordination, sharded writers, crash recovery, replay. Backend-agnostic durability layer for traditional row-oriented storage engines. Conventional ARIES-style semantics.

---

## Quick start

```toml
[dependencies]
row-wal = "0.1"
```

---

## Standards

- **REPS** governs every decision. See [REPS.md](REPS.md).
- **MSRV:** Rust 1.75.
- **Edition:** 2024.
- **Cross-platform:** Linux, macOS, Windows.

---

## License

Dual-licensed under either of:

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE))
- MIT License ([LICENSE-MIT](LICENSE-MIT))

at your option.

---

<sub>Copyright &copy; 2026 <strong>James Gober</strong>. All rights reserved.</sub>