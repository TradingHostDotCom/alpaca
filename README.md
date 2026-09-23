# TradingHost + Alpaca

Build and deploy US equity and crypto trading bots using [Alpaca](https://docs.alpaca.markets) on [TradingHost](https://tradinghost.com).

## What is this?

This repository is an AI-powered development scaffold. Use it as a template (click "Use this template" on GitHub), open your new repo in your AI coding tool (Cursor, Claude, Codex), and tell the AI what you want to build. The rules in `.cursor/rules/` teach the AI everything it needs to know about Alpaca and TradingHost to help you create a production-quality trading bot.

Alpaca offers commission-free trading for US equities and crypto with full paper trading support — perfect for developing and testing before going live.

## Getting Started

1. **Click "Use this template"** → Create a new repository (you can make it private)
2. **Open in Cursor** (or your preferred AI coding tool)
3. **Tell the AI what to build** — e.g. "Build me a momentum strategy that buys the top 5 S&P 500 movers each morning"
4. **Set credentials** — add your Alpaca API key/secret as TradingHost strategy secrets (`ALPACA_API_KEY`, `ALPACA_API_SECRET`); edit non-secret tunables (paper, symbols) in `config.json`. Secrets are environment variables, never committed to git.
5. **Deploy on TradingHost** — link this repo as a strategy, create a deployment, and you're live

## Why Alpaca?

- **Commission-free** trading for US stocks and crypto
- **Paper trading** built in — test with realistic simulation before risking real money
- **Market data included** — real-time and historical bars, quotes, and trades
- **Simple API** — REST and WebSocket with an official Python SDK (`alpaca-py`)
- **Options trading** — access to US equity options alongside stocks and crypto

## TradingHost Deployment

1. Create an account at [tradinghost.com](https://tradinghost.com)
2. Link this GitHub repository as a strategy
3. Create a deployment (choose region: London, New York, or Tokyo)
4. Your bot runs 24/7 with persistent storage, monitoring, and real-time logs

## Documentation

- [TradingHost Docs](https://tradinghost.com/docs)
- [Alpaca Documentation](https://docs.alpaca.markets)
- [alpaca-py SDK Reference](https://docs.alpaca.markets/docs/python-sdk)

## Risk Warning

Trading stocks, options, and cryptocurrencies involves significant risk of loss. This software is provided as-is with no guarantees. Always test with paper trading before using real funds. Be aware of the Pattern Day Trader (PDT) rule if your account is under $25,000.
