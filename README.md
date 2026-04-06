# USDe: A Crypto-Native Synthetic Dollar
**A technical litepaper on Ethena's delta-neutral synthetic dollar protocol**

---

## About This Document

This litepaper provides a structured technical analysis of USDe, the synthetic dollar
issued by the Ethena protocol. It covers the core mechanism design, yield architecture,
off-chain hedging infrastructure, custody model, and risk surface of one of the
fastest-growing stablecoin protocols in DeFi.

**Topics covered:**

- Why existing stablecoin models (fiat-backed, over-collateralized, algorithmic) each
  carry structural limitations
- How delta-neutral hedging enables 1:1 collateralization without directional price risk
- The three-source yield model: perpetual funding rates, Ethereum staking rewards,
  and liquid stablecoin returns
- Off-Exchange Settlement (OES) custody and how it eliminates exchange counterparty risk
- The minting and redemption mechanism, including peg arbitrage
- sUSDe as an ERC-4626 yield-bearing vault
- The off-chain Hedging System architecture
- The Reserve Fund: composition, sizing, and open market operations
- A full risk matrix covering funding, custody, oracle, smart contract, and regulatory risk
- Governance via the ENA token
All information sourced from Ethena's official documentation (docs.ethena.fi),
on-chain data, and third-party research as of Q4 2025. This document is for
informational purposes only and does not constitute financial advice.*
