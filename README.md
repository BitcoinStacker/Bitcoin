# Bitcoin Standard Calculator

https://bitcoinstacker.github.io/bitcoin/

A privacy-focused, client-side calculator for Bitcoin holders to project long-term savings in fiat terms while maintaining BTC sovereignty.

## Features

- 💰 **Multi-currency support**: USD, CNY, EUR, JPY, KRW, GBP
- 📈 **Growth projections**: Historical (50%), Conservative (40%), Bearish (30%) scenarios
- 🌓 **Dark/Light mode**: Eye-friendly interface
- 🌍 **Multi-language**: English, 中文, Español, 日本語, 한국어
- 📱 **Responsive design**: Works on all devices
- 🔒 **Zero tracking**: No analytics, no cookies, no external requests except price API

## How It Works

1. Enter any fiat amount
2. Select your currency
3. See:
   - Current BTC conversion
   - Satoshi equivalent
   - 6-year projections (BTC amount + fiat value)

## Why This Exists

As a long-term Bitcoin holder, I built this to:
- Visualize the power of holding BTC through market cycles
- Avoid spreadsheet math when checking portfolio scenarios
- Practice "don't trust, verify" with transparent calculations

## Technical Details

- **Pure client-side**: No backend required
- **Price API**: CoinGecko (can be self-hosted via [BTC RPC Explorer](https://github.com/janoside/btc-rpc-explorer))
- **Dependencies**: None (vanilla JS)

## Installation

```bash
# Just clone and open index.html!
git clone https://github.com/yourusername/bitcoin-standard-calculator.git
cd bitcoin-standard-calculator
open index.html
