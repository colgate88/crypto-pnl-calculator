# Crypto PnL Calculator

A light, Lukka-style crypto realized gain/loss calculator. Upload a CSV of spot
trades, pick FIFO/LIFO/HIFO, get back a full audit trail: sub-ledger, closed
lots, open lots, and reconciliation checks. Everything runs client-side in
your browser — no server, no data leaves your machine.

## Status

This is a learning project — first hands-on build with git, pull requests,
and deploying a static site publicly. See `MEMORY.md` in the parent folder
for the full history and roadmap.

## Run it locally

Just open `index.html` in a browser. No install, no build step.

## Input format

```
type, timestamp, base_asset, base_asset_amount, price, counter_asset, counter_asset_amount, exchange, note
```

Optional `fmv_usd` — required for crypto-to-crypto trades.
