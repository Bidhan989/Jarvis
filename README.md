# OpenJarvis

## Install

```bash
pip install -e ".[server,dev]"
pip install maturin
maturin develop --release -m rust/crates/openjarvis-python/Cargo.toml
```

Rust must be installed (the build takes about 4 minutes). Without this step, the security and memory features fail.

## Run

```bash
jarvis doctor
jarvis ask "hello"
```
