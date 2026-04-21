# Substack — Subscription Ledger

Personal subscription tracker. Records every recurring app / service you pay for, surfaces daily cost, flags unused subscriptions, warns on upcoming charges.

Single-file React app. Data stored in `localStorage` (browser-only, no backend).

## Features

- **Today** — daily amortized spend, "use it today or waste it" checklist
- **Overview** — monthly/yearly totals, category breakdown, upcoming charges
- **Ledger** — searchable/filterable list of all subscriptions
- **Calendar** — monthly renewal calendar
- **Insights** — AI recommendations, 5-year projection, payment-method risk
- **Add modal** — 65+ app templates with real logos, one-click add
- **Import / export** — JSON backup

## Stack

- React 18 + Babel standalone (CDN)
- Simple Icons for brand logos
- `localStorage` for persistence

## Run locally

Open `index.html` in a browser. That's it.

## Deploy

Push to `main` → GitHub Pages serves `index.html` at the repo URL.
