# 🧩 BitVMX Open Source Ecosystem

BitVMX is a cutting-edge platform designed to optimistically execute arbitrary programs on Bitcoin, leveraging the N-party **disputable computation** paradigm introduced by BitVM.
This repository lists all open-source components that make up the BitVMX ecosystem, from the core protocol and client libraries to tools and examples.  

> ⚠️ **Disclaimer:**  
> All projects are currently under active development. They are **not production-ready**, **not audited**, and may introduce **breaking changes** without backward compatibility in future updates.

---

## ⚙️ Core Protocol & Execution

| Project | Description |
|----------|--------------|
| [**BitVMX Client**](https://github.com/FairgateLabs/rust-bitvmx-client) | Core client for interacting with the BitVMX protocol and the Bitcoin blockchain. |
| [**BitVMX-CPU**](https://github.com/FairgateLabs/BitVMX-CPU) | The execution engine for BitVMX programs. Refer to the [BitVMX website](https://bitvmx.org/) and whitepaper for details. |
| [**BitVMX Protocol Builder**](https://github.com/FairgateLabs/rust-bitvmx-protocol-builder) | Constructs Directed Acyclic Graphs (DAGs) of pre-signed Bitcoin transactions representing protocol execution paths. |
| [**BitVMX ZK-Proof**](https://github.com/FairgateLabs/rust-bitvmx-zk-proof) | Provides Zero-Knowledge proof generation for integration with BitVMX protocols. |
| [**BitVMX Storage Backend**](https://github.com/FairgateLabs/rust-bitvmx-storage-backend) | Unified storage management layer for BitVMX components. |

---

## 🔐 Cryptography & Key Management

| Project | Description |
|----------|--------------|
| [**BitVMX Key Manager**](https://github.com/FairgateLabs/rust-bitvmx-key-manager) | Comprehensive Rust library for managing cryptographic keys and aggregated signatures used in BitVMX transactions. |
| [**BitVMX Wallet**](https://github.com/FairgateLabs/rust-bitvmx-wallet) | Bitcoin wallet implementation tailored for the BitVMX ecosystem. |

---

## 🪩 Bitcoin Integration & Infrastructure

| Project | Description |
|----------|--------------|
| [**Bitcoin Coordinator**](https://github.com/FairgateLabs/rust-bitcoin-coordinator) | Manages and monitors transaction activity within the Bitcoin network. |
| [**Bitcoin Indexer**](https://github.com/FairgateLabs/rust-bitcoin-indexer) | Extracts and stores Bitcoin block and transaction IDs for fast access and analysis. |
| [**BitVMX Transaction Monitor**](https://github.com/FairgateLabs/rust-bitvmx-transaction-monitor) | Monitors and manages multiple types of transaction watchers across the Bitcoin network. |
| [**BitVMX Bitcoin RPC**](https://github.com/FairgateLabs/rust-bitvmx-bitcoin-rpc) | Lightweight Rust interface for interacting with a Bitcoin Core node. |

---

## 🛰 Communication & Coordination

| Project | Description |
|----------|--------------|
| [**Rust BitVMX Broker**](https://github.com/FairgateLabs/rust-bitvmx-broker) | Message broker implementing synchronous and bidirectional communication channels between BitVMX clients. |
| [**BitVMX Operator Comms**](https://github.com/FairgateLabs/rust-bitvmx-operator-comms) | Operator communication layer built on top of the BitVMX Broker. |
| [**BitVMX Settings**](https://github.com/FairgateLabs/rust-bitvmx-settings) | Configuration management library supporting environment variables and file-based settings. |

---

## 🧰 Developer Tools & Utilities

| Project | Description |
|----------|--------------|
| [**bitcoin-scriptexec**](https://github.com/FairgateLabs/rust-bitcoin-scriptexec) | Bitcoin Script execution utility for testing and debugging. |
| [**Rust Bitcoin Docker**](https://github.com/FairgateLabs/rust-bitcoind) | Rust library for running and managing Bitcoin Core in Docker containers. |
| [**Docker RISCV32 Build Environment**](https://github.com/FairgateLabs/bitvmx-docker-riscv32) | Provides the RISC-V 32-bit toolchain for building programs runnable on the BitVMX-CPU. |

---

## 🎮 Examples & Demonstrations

| Project | Description |
|----------|--------------|
| [**BitVMX – Add Numbers Game**](https://github.com/FairgateLabs/bitvmx-hackathon-games) | A demonstration game where two players compete to solve an addition challenge using BitVMX verification logic. |

## 🚫 Deprecated 
This is a no longer maintained or improved PoC. If what you're looking for is the BitVMX framework, please go to [**BitVMX Client**](https://github.com/FairgateLabs/rust-bitvmx-client)
https://github.com/FairgateLabs/bitvmx_protocol

---

# 🤝 Contributing to BitVMX

We welcome contributions from the community to help expand and improve the BitVMX ecosystem.  
Before contributing, please take a moment to read the following guidelines.

---

## 🧠 How to Contribute

### 1. Reporting Issues
If you discover a bug, security issue, or unexpected behavior:
- Open an issue in the corresponding repository.
- Describe the problem clearly, including steps to reproduce, expected behavior, and relevant logs or screenshots.
- Tag the issue appropriately (e.g., `bug`, `enhancement`, `documentation`).

### 2. Suggesting Improvements
We’re continuously improving the protocols, libraries, and tooling.  
Feature proposals or design suggestions are encouraged, open a GitHub issue or discussion outlining:
- The motivation behind your idea.
- How it fits within the BitVMX architecture.
- Possible implementation approaches.

### 3. Submitting Pull Requests
To submit a code contribution:
1. Fork the target repository.
2. Create a feature branch (`git checkout -b feature/my-improvement`).
3. Implement and document your changes.
4. Run the tests and ensure all checks pass.
5. Submit a pull request with a clear summary and link to any related issues.

> 🧩 **Note:** All contributions should follow the existing Rust formatting and linting conventions (`cargo fmt`, `cargo clippy`).

---

## 🧾 Code of Conduct

Contributors are expected to maintain a respectful, collaborative, and inclusive environment.  
Disagreements are natural; disrespect is not. Please keep all interactions constructive and professional.

---

## ⚖️ License

All BitVMX projects are distributed under the **MIT License**.  
By contributing, you agree that your code will be released under the same license.

---

## 📚 Learn More

Visit [**bitvmx.org**](https://bitvmx.org/) for documentation, articles, and technical overviews of BitVMX and ongoing research
