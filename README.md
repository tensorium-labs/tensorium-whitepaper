# Tensorium Whitepaper

Technical whitepaper and mining companion pages for the Tensorium Layer 1 network.

This repository is the public protocol-facing explanation of Tensorium: consensus, tokenomics, mining posture, network ports, seed infrastructure, pool fee policy, and the developer/operator stack around the TXM chain.

## Contents

- `index.html` — primary whitepaper
- `mining.html` — operator-friendly mining guide

## Important Network Facts

- Chain ID: `tensorium-mainnet`
- P2P port: `33333/tcp`
- RPC port: `33332/tcp`
- Primary seed: `seed.tensoriumlabs.com:33333`
- Era 1 reward: `785,584,523` atoms = `7.85584523 TXM`
- Coinbase maturity: `10` blocks
- Max supply: `33,000,000 TXM` = `0` premine + `33,000,000` mining
- Pool fee: `5%`
- Pool miner endpoint: `pooltxm.tensoriumlabs.com:3333`
- Solo mining fee: `0%` at protocol level
- Pool website data scope: `pool ledger only`; direct/solo blocks remain on-chain and should be checked in the explorer
- Transaction fee posture: no protocol-enforced minimum fee at the current stage

## Intended Audience

- Miners evaluating solo vs pool operation
- Developers building on top of TXM
- Integrators who need canonical network constants
- Reviewers who want the tokenomics and security model in one place

## License

Apache-2.0
