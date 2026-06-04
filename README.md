# Tensorium Whitepaper

Technical whitepaper and mining companion pages for the Tensorium Layer 1 network.

This repository is the public protocol-facing explanation of Tensorium: consensus, tokenomics, mining posture, network ports, seed infrastructure, pool fee policy, and the developer/operator stack around the TXM chain.

## Contents

- `index.html` — primary whitepaper
- `mining.html` — operator-friendly mining guide

## Important Network Facts

- Chain ID: `tensorium-mainnet-candidate-0`
- P2P port: `33333/tcp`
- RPC port: `33332/tcp`
- Primary seed: `seed.tensoriumlabs.com:33333`
- Secondary seed: `seed2.tensoriumlabs.com:33333`
- Backup seed naming: expose the hostname, not the raw VPS IP
- Era 1 reward: `1,190,279,581` atoms = `11.90279581 TXM`
- Max supply: `33,000,000 TXM` = `8,000,000` pre-mint + `25,000,000` mining
- Pool fee: `5%`
- Solo mining fee: `0%` at protocol level
- Transaction fee posture: no protocol-enforced minimum fee at the current stage

## Intended Audience

- Miners evaluating solo vs pool operation
- Developers building on top of TXM
- Integrators who need canonical network constants
- Reviewers who want the tokenomics and security model in one place

## License

Apache-2.0
