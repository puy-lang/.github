<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="puy-logo-dark.svg">
    <img src="puy-logo.svg" alt="Puy" width="320">
  </picture>
</p>

<p align="center">
  An Object Pascal implementation modeled on the feel of writing Delphi code.
</p>

<p align="center">
  <a href="https://puy-lang.org">Website</a> ·
  <a href="https://github.com/puy-lang/puy">Source</a> ·
  <a href="https://crates.io/crates/puy">crates.io</a>
</p>

---

Puy compiles Pascal source to bytecode and runs it on a stackless VM written in Rust,
aiming at single native binaries, WASI and the browser from the same source.

- **Familiar Pascal.** Delphi's syntax, deterministic lifetime management, and the names
  of commonly used units and routines.
- **Modern features.** Dynamic arrays, slices and collections follow modern languages
  such as Python, Go and Rust.
- **Safe by default.** Mistakes are reported as compile errors or exceptions instead of
  passing silently.
- **Written by people and coding agents.** Knowledge of Delphi carries over, and
  diagnostics come with suggested fixes and machine-readable output.

```sh
cargo install puy
```

```pascal
program Hello;

begin
  WriteLn('Hello, Puy!');
end.
```

Puy is in early development. It does not promise compatibility with Delphi or Free
Pascal.

## Repositories

| Repository | Description |
|---|---|
| [puy](https://github.com/puy-lang/puy) | The compiler, VM, runtimes and the `puy` command |
| [puy-lang.github.io](https://github.com/puy-lang/puy-lang.github.io) | The built website served at [puy-lang.org](https://puy-lang.org) |

Puy is developed in a separate repository; the public repositories receive a snapshot
for each release. Issues and pull requests are not accepted for now.
