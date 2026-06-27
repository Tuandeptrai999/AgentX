<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=AgentX%20Network&fontSize=50&animation=fadeIn" width="100%"/>
  <br/>
  <img src="./canopy-logo-white-bg.svg" alt="Canopy Logo" width="250"/>
</div>

_The Next-Generation Decentralized Infrastructure for Autonomous AI Agents._

<p align="center">
  <a href="https://godoc.org/github.com/Tuandeptrai999/canopy"><img src="https://img.shields.io/badge/godoc-reference-white.svg" alt="GoDoc"></a>
  <a href="https://testnet.app.canopynetwork.org/chains/632815"><img src="https://img.shields.io/badge/Testnet-Active-00C853?style=flat&logo=rocket" alt="Testnet Active"></a>
  <a href="https://golang.org"><img src="https://img.shields.io/badge/golang-v1.21-blue.svg?logo=go" alt="Go Version"></a>
  <img src="https://img.shields.io/badge/Chain%20ID-632815-FF5722?style=flat&logo=blockchain" alt="Chain ID">
  <img src="https://img.shields.io/badge/Token-AGXX-F4D03F?style=flat&logo=ethereum" alt="Token">
</p>

# 📖 Overview

### 🤖 What is AgentX?
**AgentX** is a sovereign, high-performance blockchain network built on the robust Canopy protocol. It is specifically engineered to act as the foundational layer for **Decentralized Autonomous Agents**. By providing a secure, high-throughput, and infinitely scalable environment, AgentX empowers AI agents to seamlessly interact, transact, and execute complex workflows without human intervention. 

### 🎯 What Problems Does It Solve?
Current blockchains are built for human-to-smart-contract interactions, which are often slow and expensive for automated agents. AgentX solves this by providing:
- **Agent-to-Agent Economy:** Creates a frictionless environment where AI agents can autonomously negotiate and pay each other using the native **AGXX** token.
- **Scalable Consensus:** Utilizes a highly optimized BFT consensus mechanism that guarantees finality in milliseconds, crucial for real-time AI decision making.
- **Interoperability:** Natively bridges across the Canopy ecosystem, allowing agents to fetch data and trigger actions across multiple networks seamlessly.

### 🌳 Powered by Canopy
**AgentX** is proudly built on and runs under the **Canopy Network** protocol. 
Canopy is a revolutionary peer-to-peer launchpad for new chains. It utilizes a recursive architecture where chains bootstrap each other into independence, forming an unstoppable web of utility and security. By leveraging Canopy's terminal and core infrastructure, AgentX inherits enterprise-grade security, rapid deployment capabilities, and native cross-chain interoperability from day one.
---

# 💎 AGXX Token Utility
The **AGXX** token is the lifeblood of the AgentX ecosystem. Its core utilities include:
1. **Transaction Fees (Gas):** Used by autonomous agents to pay for computation and network state changes.
2. **Staking & Security:** Validators and delegators stake AGXX to secure the network and earn block rewards.
3. **Agent Registration:** Developers burn or lock AGXX to register their AI agents onto the network registry.
4. **Governance:** AGXX holders can vote on critical protocol upgrades and parameter changes.

---

# 🗺️ Roadmap

- [x] **Phase 1: Foundation (Current)**
  - Launch AgentX Testnet (Chain ID: 632815).
  - Deploy core P2P networking and BFT consensus modules.
- [ ] **Phase 2: The Agent SDK**
  - Release the AgentX Golang SDK for seamless AI integration.
  - Implement smart contract support for basic agent escrow services.
- [ ] **Phase 3: Mainnet Launch**
  - Genesis block generation.
  - Public validator onboarding and delegation program.
- [ ] **Phase 4: Ecosystem Expansion**
  - Cross-chain interoperability bridges.
  - Agent marketplace and decentralized AI registry.

---

## 💻 Technical Architecture

Welcome to the AgentX reference implementation. The repository is modularized into several core components:

- [**Controller**](controller/README.md): Coordinates communication between all the major parts of the blockchain, acting as the central hub.
- [**Finite State Machine (FSM)**](fsm/README.md): Defines the logic for how transactions change the blockchain's state.
- [**BFT Consensus**](bft/README.md): A robust consensus mechanism allowing the network to agree on new blocks.
- [**Peer-to-Peer Networking**](p2p/README.md): Secure and encrypted communication between validator nodes.
- [**Persistence**](store/README.md): Manages the blockchain’s storage and indexes past transactions.

## 🚀 How to Run It

To run the AgentX binary locally:

```bash
make build/agentx-full
agentx start
```

### 🐳 Run with Docker

To run an AgentX `Localnet` in a containerized environment:

```bash
make docker/build
make docker/up-fast
make docker/logs
```

## 🤝 How to Contribute
AgentX is an open-source movement! 
1. **Fork** the repository.
2. **Code** your improvements.
3. **Submit a Pull Request** against the `development` branch.

<p align="center">
  <br/>
  <i>Built with ❤️ by Tuandeptrai999 & the AgentX Community</i>
</p>
