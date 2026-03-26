# TONOracle MCP Server

**11 DeFi risk & compliance intelligence tools for the TON ecosystem.**

Built for AI agents operating in the Telegram/TON ecosystem — 950M+ potential users.

## Live Endpoint

```
https://tooloracle.io/ton/mcp/
```

No API key required. MIT licensed.

## Quick Setup

```json
{
  "mcpServers": {
    "tonoracle": {
      "url": "https://tooloracle.io/ton/mcp/"
    }
  }
}
```

## Tools (11)

| Tool | Description | Data Source |
|------|-------------|------------|
| `ton_overview` | TON ecosystem: price, TVL, protocol count, Telegram integration | CoinGecko + DeFiLlama |
| `ton_wallet_info` | Wallet balance and state by address | TONCenter |
| `ton_jetton_check` | Jetton (TON token) risk analysis — contract state, CoinGecko listing | TONCenter + CoinGecko |
| `ton_protocol_health` | Protocol health: TVL, audits, risk grade (DeDust, Ston.fi, EVAA...) | DeFiLlama |
| `ton_defi_yields` | Compare DeFi yields across TON protocols | DeFiLlama Yields |
| `ton_protocol_list` | All TON DeFi protocols ranked by TVL | DeFiLlama |
| `ton_stablecoin_risk` | Stablecoin supply and risk on TON | DeFiLlama |
| `ton_dex_volume` | DEX volume across TON exchanges (DeDust, Ston.fi) | DeFiLlama DEX |
| `ton_bridge_flows` | Bridge flow monitoring | DeFiLlama Bridges |
| `ton_network_stats` | Masterchain info: seqno, workchain, shard | TONCenter |
| `ton_transactions` | Recent transactions for any TON address | TONCenter |

## Data Sources

- **TONCenter API** — Wallet info, transactions, contract state
- **DeFiLlama** — TVL, yields, stablecoins, DEX volumes, bridges
- **CoinGecko** — Prices, market data

## Links

- **Live endpoint**: https://tooloracle.io/ton/mcp/
- **Health check**: https://tooloracle.io/ton/health
- **Builder**: [FeedOracle Technologies](https://feedoracle.io) — EU-based compliance infrastructure
- **Marketplace**: [ToolOracle](https://tooloracle.io)
- **License**: MIT
