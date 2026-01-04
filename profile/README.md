# Ethereum on ARM

Ethereum on ARM is an open-source project that builds and maintains ready-to-use Linux images, packages, and tools that turn affordable ARM64 single-board computers into fully featured Ethereum nodes and staking machines with minimal manual setup.

The project’s mission is to lower the barrier to running Ethereum infrastructure by making nodes more accessible, energy-efficient, and sustainable for individuals, educators, and small operators.

Ethereum on ARM supports both Layer 1 and Layer 2 infrastructure, allowing you to run execution clients, consensus clients, validators, and OP-Stack–based networks on low-power hardware at home or in small labs.

---

## What you can run

### Ethereum Layer 1
- Execution clients: Geth, Nethermind, Erigon, Besu, Reth
- Consensus clients: Lighthouse, Prysm, Teku, Nimbus, Lodestar, Grandine
- Full nodes, archive nodes, and validator setups

### Layer 2 / Rollups
- OP-Stack components (op-node, op-geth, proposer, challenger)
- Other EVM-compatible networks where ARM support is practical

All components are optimized for ARM64 boards such as Raspberry Pi, Rock 5, Orange Pi, and similar devices.

---

## How to get involved

### Contribute
- Open an issue: https://github.com/ethereum-on-arm/ethereum-on-arm/issues  
  Report bugs, request support for new boards, or suggest features.
- Submit pull requests: https://github.com/ethereum-on-arm/ethereum-on-arm/pulls  
  Contributions are welcome for images, scripts, monitoring, automation, and documentation.
  Hardware notes, benchmarks, and real-world testing reports are especially valuable.

### Join the community
- Discord: https://discord.gg/ethereum (look for the #arm channel)
- Farcaster: https://warpcast.com/ethereumonarm
- X (Twitter): https://twitter.com/EthereumOnARM

---

## Getting started

- Documentation:  
  https://ethereum-on-arm-documentation.readthedocs.io/en/latest/  
  Includes quick start guides, user documentation, and advanced topics to get you from flash to fully synced.

- Releases:  
  https://github.com/ethereum-on-arm/ethereum-on-arm/releases  
  Download prebuilt images for supported ARM boards.

- Background reading:  
  https://ethereum.org/en/run-a-node/  
  Official Ethereum guide explaining what it means to run a node.

---

## Why ARM?

- Low power consumption (often around 10 W)
- Affordable hardware
- Silent, always-on operation
- Ideal for home labs, education, and decentralization at the edge

---

## Fun facts

- You can run a full node — and even an archive node plus a validator — on a sub-$200 ARM board.
- Some users have been running Ethereum on ARM continuously for years, upgrading hardware while keeping the same node alive.
- Small ARM clusters behind home routers help keep Ethereum decentralized and resilient.

---

## License

Ethereum on ARM is released under open-source licenses.  
See individual repositories for license details.
