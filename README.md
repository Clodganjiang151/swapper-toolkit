# Swapper Toolkit

DeFi toolkit for AI agents and coding assistants — deposit funds, execute trades, and manage crypto wallets. Works with Claude Code, Cursor, Windsurf, OpenClaw, CrewAI, AutoGPT, and other AI agent frameworks.

## Installation

```bash
npx skills add swapper-finance/swapper-toolkit
```

## Skills

### Swapper Deposit

Deposit and bridge funds into wallets and protocols.

```
/swapper-deposit
```

- Direct deposits to wallet addresses
- Cross-chain bridge transfers
- Protocol deposits (lending, staking, liquidity pools)
- Fiat on-ramp funding (where supported)

### Swapper Trade

Execute token swaps and trades across DEXs and aggregators.

```
/swapper-trade
```

- Token-to-token swaps
- Market and limit orders (where supported)
- Multi-hop routing for best execution
- Cross-chain swaps via bridge + DEX

### Swapper Wallet Management

Create, import, list, and manage crypto wallets and keys.

```
/swapper-wallet-management
```

- Create new wallets (EVM, Solana, and other supported chains)
- Import wallets from mnemonic, private key, or keystore
- List wallets and balances
- Export keys (with explicit consent)
- Label and organize wallets

## Safety

All skills enforce strict safety rules:

- Explicit user confirmation is required before any transaction or sensitive action
- Transactions are never auto-approved
- Slippage, gas fees, and risks are surfaced before execution
- Private keys and mnemonics are never stored in plain text

## License

[MIT](LICENSE)
