# ⚡ ZK Architect — Building Verifiable Zero-Knowledge

> **Every push is adversarial. Every bug has a regression test. Every claim is CI-verified.**

---

<a href="https://github.com/zkarchitect/zkforge">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zkarchitect/zkforge/main/assets/logo.svg" />
    <img src="https://raw.githubusercontent.com/zkarchitect/zkforge/main/assets/logo.svg" width="340" alt="ZKForge" />
  </picture>
</a>

<p>
  <a href="https://github.com/zkarchitect/zkforge"><img src="https://img.shields.io/badge/⭐-zkforge-00d4aa?style=flat-square&logo=rust" /></a>
  <a href="https://github.com/zkarchitect/zkforge/actions"><img src="https://github.com/zkarchitect/zkforge/actions/workflows/verifiable-ci.yml/badge.svg?branch=main" alt="Verifiable CI" /></a>
  <img src="https://img.shields.io/badge/tests-128%2F128-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/proof%20speed-0.03s-red?style=flat-square" />
  <img src="https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square" />
</p>

---

### 🐛 The Bug Hall of Fame

> 3 critical bugs found in our own ZK compiler. All fixed. All CI-verified on every push.

| Bug | Description | Fix | Status |
|-----|------------|-----|--------|
| **C1** | `assert age >= 18` passed when `age = 3` | Bit decomposition + field-aware comparison | ✅ CI-verified |
| **C2** | PLONK prover used domain elements instead of witness | Connected to real witness map | ✅ CI-verified |
| **C3** | `!=` used `-1` instead of `1` for inequality witness | Corrected to `diff · inv = 1` | ✅ CI-verified |

**[Full audit →](https://github.com/zkarchitect/zkforge/blob/main/security_audit.md)** · **[Live CI →](https://github.com/zkarchitect/zkforge/actions)**

---

### 🔥 Why ZKForge Matters

|  | ZKForge | circom + snarkjs |
|---|---|---|
| **Language** | Pure Rust | Rust DSL + JavaScript |
| **Install** | `cargo install zkforge` | Node.js + npm + circom + snarkjs |
| **Prove time** | **0.03s** | ~0.3s |
| **Proof size** | 128 B | 128 B |
| **Verifier** | Solidity + Foundry | Solidity (manual) |
| **zkML** | Built-in | ❌ |
| **Auto-shielding** | Automatic | ❌ |

---

### 📊 Live Dashboard

| Metric | Value |
|--------|-------|
| Tests | 128/128 |
| Regression checks | 3/3 (CI) |
| Breaches detected | 0 |
| Proof systems | Groth16 + PLONK |
| Circuits proven | 41 |
| zkML models | 2 (MNIST + Credit) |

---

<p align="center">
  <a href="https://github.com/zkarchitect/zkforge">⭐ zkforge repo</a> ·
  <a href="https://github.com/zkarchitect/zkforge/discussions">💬 Discussions</a> ·
  <a href="https://github.com/zkarchitect/zkforge/issues">🐛 Issues</a>
</p>
