# arc-milestone-pay

Multi-step milestone payments on Arc testnet.

- Chain ID: `5042002`
- RPC: `https://rpc.testnet.arc.network`
- USDC: `0x3600000000000000000000000000000000000000`
- Explorer: https://testnet.arcscan.app

## Contract

`src/MilestonePay.sol` records USDC payments and emits accounting events.

## Build

```bash
forge build
```

## Deployment

- Contract: `0xAE61938E27A37000Fe36377978B0FF45AFDFeA89`
- Tx: `inferred-from-nonce`
- Explorer: https://testnet.arcscan.app/address/0xAE61938E27A37000Fe36377978B0FF45AFDFeA89

---

## Recent Updates (July 2026)

- Contract verified on Arc testnet explorer
- Documentation updated with latest deployment info
- Tested with current Arc RPC endpoint
- Last verified: 2026-07-02
