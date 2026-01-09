# FerroxOS

<div align="center">

![FerroxOS](https://img.shields.io/badge/FerroxOS-Rust_Powered-orange?style=for-the-badge&logo=rust)
![Status](https://img.shields.io/badge/Status-In_Development-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-GPLv3-green?style=for-the-badge)

**A modern Linux distribution built on memory safety, immutability, and atomic updates**

*Rust Never Sleeps, Neither Does Security*

</div>

---

## 🦀 What is FerroxOS?

FerroxOS is an **immutable Linux distribution** with a Rust-native userland, designed for security-conscious developers and professionals who demand both cutting-edge safety and rock-solid reliability.

### Core Features

🛡️ **Memory-Safe Userland** — Rust eliminates entire classes of vulnerabilities  
⚛️ **Atomic A/B Updates** — Update with confidence, rollback instantly  
📦 **Content-Addressable Storage** — Deduplicated, generational package management via `rox`  
🎨 **COSMIC Desktop** — Beautiful, Rust-based desktop environment  
🔒 **Security-First** — Immutable root, verified boot, encrypted home  
⚡ **Lightning Fast** — Sub-10 second boot times, optimized performance  

## 🚀 Quick Start

```bash
# Install a package
sudo rox install firefox

# System upgrade
sudo rox upgrade

# Instant rollback
sudo rox rollback
```

## 🏗️ Architecture

- **Linux Kernel** — Proven foundation with Rust driver support
- **ignite** — Custom Rust initramfs with integrity verification
- **ignited** — Modern PID 1 init system replacing systemd
- **rox** — Next-gen package manager with CAS and generations
- **COSMIC DE** — Wayland-native desktop by System76

## 🌟 Why FerroxOS?

Traditional distributions face memory corruption vulnerabilities and configuration drift. FerroxOS solves this through:

- **Immutability** — Read-only root prevents malware persistence
- **Memory Safety** — Rust's guarantees protect against 70% of CVEs
- **Generations** — Time-travel your system state with instant rollback
- **Declarative Config** — System state as code

## 🤝 Contributing

We welcome contributions! Check out our repositories:

- [ferroxos](https://github.com/FerroxOS/ferroxos) — Main system build
- [ignite](https://github.com/FerroxOS/ignite) — Boot system (initramfs)
- [ignited](https://github.com/FerroxOS/ignited) — Init system (PID 1)
- [rox](https://github.com/FerroxOS/rox) — Package manager
- [ferrox-build](https://github.com/FerroxOS/ferrox-build) — Build tooling

See [CONTRIBUTING.md](https://github.com/FerroxOS/.github/blob/main/CONTRIBUTING.md) for guidelines.

## 📅 Roadmap

- **Q2 2026** — Alpha release
- **Q3 2026** — Beta testing
- **Q4 2026** — Stable 1.0 release


## 📜 License

- **System Components**: GPLv3
- **Libraries**: MIT/Apache-2.0

---

<div align="center">

**Built with 🦀 by the FerroxOS community**

*Security through memory safety. Reliability through immutability.*

</div>
