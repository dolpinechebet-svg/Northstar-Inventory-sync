# Northstar Inventory Sync Demo

A live demo built for Northstar Retail Co. (Sprint 2), showing how store-floor
inventory events sync in real time with the support tool's "is this in stock?"
lookup.

## View it

- **Live:** `https://<your-username>.github.io/<repo-name>/`
- **Locally:** download `inventory-sync-demo.html` and open it in any browser.
  No build step or server required.

## What it shows

- **Store floor feed** — a live log of register sales, warehouse restocks,
  and multi-channel stock conflicts as they happen.
- **Support tool preview** — the agent-facing stock lookup, with quantities,
  status (in stock / low / out), and a synced indicator that updates the
  moment a new event comes in.
- **System health strip** — sync latency, event rate, and open discrepancies,
  including an auto-reconcile step when a conflict is detected.

Use the buttons at the bottom of the page to trigger a sale, a restock, or a
conflict manually, or turn on autoplay to let events run continuously during
a walkthrough.

## Status

This is a front-end simulation for review purposes. It uses generated demo
data and is not connected to any live POS, warehouse, or inventory system.
