# Ethereum on ARM

Ethereum on ARM turns affordable ARM64 single board computers into fully featured Ethereum L1/L2 nodes and staking boxes with minimal setup.[web:1][web:9]

## What this project provides

- Prebuilt Ubuntu/Armbian images for popular ARM64 boards (e.g. NanoPC‑T6, Rock 5B, Orange Pi 5 series).[web:1]
- Systemd‑managed Execution and Consensus clients for Ethereum mainnet and testnets.[web:1][web:9]
- Optional L2 nodes (Optimism, Arbitrum, Polygon, Starknet, Gnosis) on the same device.[web:1][web:14]
- EOA‑gui console menu to configure L1/L2 full or archive nodes interactively (alpha stage).[web:1]
- Integrated monitoring via Prometheus and Grafana dashboards.[web:1][web:14]
- Tuned OS settings and packages for stable, low‑power, always‑on node operation.[web:1][web:9]

## Why run Ethereum on ARM?

- Strengthens Ethereum decentralization by making it easy to run nodes at home on small, low‑power hardware (~10 W typical).[web:9][web:12]
- Enables affordable solo staking or DVT setups on off‑the‑shelf ARM64 boards.[web:1][web:11]
- Supports both L1 and L2 infrastructure, including OP Stack‑based networks.[web:4][web:11]

## Getting started

1. **Read the docs**  
   Visit the full documentation for supported boards, images, and step‑by‑step guides:  
   https://ethereum-on-arm-documentation.readthedocs.io[web:9][web:19]

2. **Download an image**  
   Pick your board and download the latest image from the releases page of this repository.[web:1]

3. **Flash and boot**  
   Flash the image to an SD card or SSD, insert it into your board, and boot.  
   The system will auto‑provision services to run your chosen Ethereum clients.[web:9]

4. **Configure your node**  
   Use `EOA-gui` or the CLI tools to select network (mainnet, testnets, L2s), client combinations, and node type (full, archive, validator).[web:1][web:14]

## Documentation and resources

- Main docs: https://ethereum-on-arm-documentation.readthedocs.io[web:9]
- Features overview: main features and architecture diagrams in the docs.[web:14]
- How to run an Ethereum node (background reading): https://ethereum.org/run-a-node/[web:7][web:20]

## Community and support

- Discord: Join the community chat for support and discussion (link in repo description/docs).[web:1][web:9]
- Farcaster: `@ethereumonarm` for ecosystem updates.[web:18]
- X (Twitter): https://x.com/EthereumOnARM[web:12]

## Contributing

Contributions are welcome:

- Improve board support, build scripts, or images.
- Add or update Execution/Consensus/L2 client integrations.
- Enhance monitoring, documentation, and testing.

Please open an issue or pull request in this repository to get started.[web:1]

## License

This project is licensed under the GPL‑3.0 license, as indicated in the main repository.[web:1]
