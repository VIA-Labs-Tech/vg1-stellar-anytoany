# vg1-stellar-anytoany

VIA Labs will open-source the Soroban smart contracts for AnyToAny on Stellar and release them in this repository. Soroban is Stellar's smart contract platform.

AnyToAny is the all-in-one bridge, swap, and router. On Stellar, it will move tokens between EVM chains and Stellar with one signature, through Circle's CCTP v2 and LayerZero, and swap on Stellar through Soroswap and Aquarius.

## What will be here

- The source code of the AnyToAny Stellar contract. It receives each delivery, checks it against the route VIA signed, swaps on a Stellar DEX, and pays the user.
- A verifiable build, so anyone can check that the deployed contract matches the published code.

The code will be released here under the Apache 2.0 license by mainnet launch at the latest.

## Already public

- Developer docs: https://developer.vialabs.tech
- Audit reports: https://developer.vialabs.tech/docs/general/audits
- Every VIA transfer, on VIA Scan: https://scan.vialabs.tech
- AnyToAny: https://anytoany.xyz
