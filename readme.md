<div align="center">
  <img src="https://raw.githubusercontent.com/zkarchitect/zkforge/main/assets/logo.svg" alt="ZKForge" width="360" />

  <h3>Pure Rust ZK Compiler — No circom. No snarkjs. No Node.js.</h3>

  <p>
    <a href="https://github.com/zkarchitect/zkforge"><img src="https://img.shields.io/badge/zkforge-Pure%20Rust%20ZK%20Compiler-00d4aa?style=flat-square&logo=rust" /></a>
    <a href="https://github.com/zkarchitect/zkforge/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square" /></a>
    <img src="https://img.shields.io/badge/proof%20speed-0.03s-red?style=flat-square" />
    <img src="https://img.shields.io/badge/systems-Groth16%20%7C%20PLONK-blueviolet?style=flat-square" />
  </p>

  <hr width="50%" />

  <h3>📊 zkforge in Numbers</h3>

  | Metric | Value |
  |--------|-------|
  | Proving time (simple circuit) | **0.03s** |
  | Proof size | **128 bytes** |
  | Test suite | **128/128 passing** |
  | Lines of Rust | **~3,500** |
  | Proof systems | **Groth16 + PLONK** |
  | Verifier output | **Solidity (EIP-197) + Foundry deploy** |

  <hr width="50%" />

  <h3>🔥 What Sets zkforge Apart</h3>

  <table>
    <tr><td>🚀</td><td><strong>0.03s proving</strong> — 10x faster than circom/snarkjs</td></tr>
    <tr><td>🦀</td><td><strong>Pure Rust</strong> — one language, one binary, no JavaScript</td></tr>
    <tr><td>🧠</td><td><strong>Built-in zkML</strong> — neural network inference in zero knowledge</td></tr>
    <tr><td>🔐</td><td><strong>Auto-Shielding</strong> — wrap any contract with ZK privacy automatically</td></tr>
    <tr><td>🔄</td><td><strong>Recursive proofs</strong> — compose proofs natively</td></tr>
    <tr><td>📦</td><td><strong>One-command deploy</strong> — Solidity verifier + Foundry package</td></tr>
    <tr><td>🛡️</td><td><strong>Security audited</strong> — 3 critical bugs found and fixed</td></tr>
  </table>

  <hr width="50%" />

  <h3>📦 Quick Install</h3>

  ```bash
  cargo install zkforge
  zkforge prove my_circuit.zkf
  zkforge deploy my_circuit.zkf --chain-id 11155111
  ```

  <hr width="50%" />

  <p>
    <a href="https://github.com/zkarchitect/zkforge">🔗 zkforge repo</a> ·
    <a href="https://github.com/zkarchitect/zkforge/discussions">💬 Discussions</a> ·
    <a href="https://github.com/zkarchitect/zkforge/issues">🐛 Issues</a>
  </p>
</div>